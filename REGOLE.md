# Solitario di Napoleone: regole

Regole del Solitario di Napoleone, scritte con Matteo il 13 ottobre 2026.

## Mazzo

40 carte piacentine: Denari, Coppe, Spade, Bastoni.
Ordine dei valori: Asso (1), 2, 3, 4, 5, 6, 7, Fante (8), Cavallo (9), Re (10).

## Disposizione iniziale

1. Si tolgono i quattro Assi dal mazzo e si mettono in colonna, uno sotto l'altro, al centro del tavolo, in quest'ordine: Denari, Spade, Bastoni, Coppe. Sono le **basi**.
2. Si mescolano le 36 carte rimaste e si distribuiscono a caso in **8 righe**, una a sinistra e una a destra di ogni Asso:

| Asso      | Carte a sinistra | Carte a destra |
|-----------|------------------|----------------|
| Denari    | 5                | 5              |
| Spade     | 5                | 5              |
| Bastoni   | 4                | 4              |
| Coppe     | 4                | 4              |

   Totale: 10 + 10 + 8 + 8 = 36 carte.
3. In ogni riga le carte sono scoperte e in parte sovrapposte, in modo che si vedano tutte.
4. La carta **libera** di una riga è quella più lontana dall'Asso: la più a sinistra nelle righe di sinistra, la più a destra nelle righe di destra. Solo questa carta si può spostare.

## Scopo

Portare sopra ogni Asso tutte le carte del suo seme, in ordine crescente, fino al Re.

## Fine partita

La partita è vinta quando tutte le 40 carte sono sui quattro mazzetti al centro, ognuno con le carte del proprio seme dall'Asso al Re.

## Mosse

Si sposta una sola carta alla volta, e solo se è libera. Può andare in tre posti:

1. **Sulla base del suo seme**, se ha un punto in più della carta in cima alla base.
   Esempio: il 2 di Spade va sull'Asso di Spade.
   Una carta messa su una base non si può più riprendere.
2. **Su una riga vuota**: va bene qualsiasi carta.
3. **Su un'altra riga**, sopra la sua carta libera, se quella carta:
   - è di **seme diverso**, e
   - ha **un punto in più**.

   Esempio: il 4 di Bastoni va sul 5 di Spade.
   Non sono valide: il 4 di Coppe sul 4 di Coppe, il 5 di Spade sul 7 di Denari, il 5 di Spade sul 3 di Coppe.

## Partita persa

La partita è persa, e si riparte con una nuova distribuzione delle carte, quando:

- non ci sono più mosse possibili, oppure
- le mosse rimaste non possono più portare tutte le carte sugli Assi, per esempio perché si può solo spostare avanti e indietro la stessa carta. Il gioco lo verifica da solo dopo ogni mossa.

## Piattaforma

Si gioca nel browser, su computer e telefono. Il codice è in questo repository: il gioco è tutto nel file `index.html`.
