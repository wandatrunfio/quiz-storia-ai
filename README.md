# Quiz: la storia dell’IA

Da Turing a ChatGPT: 15 domande sulle tappe che hanno portato all’intelligenza artificiale di oggi.

Quiz interattivo del *Corso per formatori sull’uso dell’IA a scuola*, a cura di Wanda Trunfio.
Le domande e le risposte compaiono in ordine casuale; dopo ogni risposta il quiz mostra la spiegazione e la fonte.
Alla fine si vedono il punteggio, il tempo e il riepilogo delle risposte, e si può rifare il quiz.

Il sito è composto da `index.html` e dal logo `logo.png`, senza dipendenze da installare. Non salva dati e non usa cookie.

## Pubblicarlo con GitHub Pages

1. Crea un nuovo repository su GitHub, ad esempio `quiz-storia-ia`, e carica `index.html`, `logo.png` e `README.md` (Add file › Upload files).
2. Vai in **Settings › Pages**.
3. In **Build and deployment** scegli *Deploy from a branch*, il branch `main` e la cartella `/ (root)`, poi **Save**.
4. Dopo uno o due minuti il quiz è online all’indirizzo `https://<tuo-utente>.github.io/quiz-storia-ia/`.

## Modificare le domande

Le domande sono nella costante `Q` dentro `index.html`. Ogni domanda ha questa forma:

```
["Testo della domanda", ["Risposta A", "Risposta B", "Risposta C", "Risposta D"], 0, "Spiegazione", "Fonte"]
```

Il numero (da 0 a 3) indica la risposta corretta nell’elenco.
