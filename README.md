# Preventivatore LCM Marchioni – prototipo

Pagina statica che calcola il preventivo di pezzi su misura in marmo, granito, quarzo e sinterizzato.
Legge tutti i costi da `listino.xlsx`.

## File
- `index.html` – il preventivatore (un solo file, nessun server necessario)
- `listino.xlsx` – listino di esempio: materiali, classi, spessori, macchine, lavorazioni, modelli, accessori, parametri

## Pubblicazione su GitHub Pages
1. Carica `index.html` e `listino.xlsx` nella root del repository.
2. Settings → Pages → Branch `main`, cartella `/ (root)`.
3. Apri l'indirizzo GitHub Pages: la pagina legge `listino.xlsx` dalla stessa cartella.

Se il file non viene trovato (es. aprendo `index.html` dal disco), la pagina usa il listino di esempio integrato.
Con il pulsante **Carica listino Excel** si può provare un listino diverso senza pubblicarlo.

## Aggiornare i dati
Modifica `listino.xlsx` (testo blu = dati, celle grigie = formule) e ricaricalo nel repository.
Non rinominare i fogli né le intestazioni della riga 1.

> Attenzione: il repository GitHub Pages è pubblico. Con i prezzi reali di LCM usare un repository privato
> (Pages privato richiede un piano a pagamento) oppure passare all'integrazione AppSheet / Google Sheets.
