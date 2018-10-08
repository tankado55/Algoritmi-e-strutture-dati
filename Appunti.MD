# Insertion Sort

# Cap.6 Heapsort

Un heap è una struttura dati composta da un array che possiamo considerare come un albero binario.
I valori nei nodi soddisfano una proprietà dell'heap. In un max-heap , la proprietà è che per ogni nodo i, A[Parent(i)] >= A[i], in un min-heap è l'opposto.
L'altezza di un heap è log(n).

# Esame settembre 2018

1. Si consideri un max-heap H contenente 80 chiavi distinte. In quante possibili posizioni può trovarti la chiave minima di H? Le possibili soluzioni sono: 32 - 40 - 41 - 42 - 64
> Soluzione: 64, la chiave minima sta nella profondità massima, la profondità di un albero è log(n), per trovare il numero di elementi alla massima profondità basta fare 2^"profondità albero"
