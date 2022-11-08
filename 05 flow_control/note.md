Ho svolto l'esercizio con "mix" perché per quanto provassi a riscrivere il codice usando darken, lighten, o modificando "lightness" in color.adjust mi continuava a comparire questo errore:

Error: $amount: calc(1 * 5) is not a number.

Mi dà lo stesso errore anche eliminando il calc e lasciando solo l'indice (anche nel caso sia scritto così: #{$i} ), cioè compare "1 is not a number".

Inizialmente avevo creato la variabile "percentage" in cui calcolare la percentuale da passare in base all'indice i del for loop oltre che provare a scrivere il "calc" direttamente come parametro da passare alla funzione.

Ex.
$percentage: calc(#{$i} * 5);

Ho provato a riscriverlo con e senza cancelletto e spostandolo in diverse posizioni, oltre che scrivendo o omettendo il simbolo di percentuale, anche aggiungendolo come stringa fuori dal risultato, ma inutilmente. Cercando ho letto che può essere un conflitto tra sass e gli aggiornamenti di css (https://css-tricks.com/when-sass-and-new-css-features-collide/) ma non so se fosse quello il problema - la soluzione proposta, ossia quella di sfruttare le maiuscole e il fatto che sass sia case sensitive e css no, mi ha permesso di aggirare l'errore e il file css veniva compilato, tuttavia non funzionava. In attesa di una prossima live, lascio l'esercizio svolto in modo parzialmente diverso rispetto all consegna.