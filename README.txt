REEKO WEBAR DEMO — MARKER UNIVERSALE

CONTENUTO
- index.html        -> esperienza AR
- marker.html       -> marker Hiro da stampare o mostrare su un altro schermo
- reeko-overlay.png -> elemento grafico che compare sopra il marker

COME PROVARLA
1. Pubblica questa cartella su un hosting HTTPS.
   Esempi semplici: Netlify Drop, GitHub Pages, Vercel.
2. Apri index.html dal telefono tramite l'URL HTTPS.
3. Consenti l'accesso alla fotocamera.
4. Stampa marker.html oppure aprilo su un altro schermo.
5. Inquadra il marker Hiro.
6. Sopra il marker comparirà la grafica Reeko animata.
7. Il bottone “Scopri Reeko” apre https://www.reeko.co/

IMPORTANTE
Il supporto fisico NON è rilevante:
puoi stampare/serigrafare/incidere lo stesso marker su carta, cartone, legno,
packaging o altro. Quello che deve essere riconoscibile è il marker visivo.

PERCHÉ SERVE HTTPS
I browser mobili richiedono un contesto sicuro per concedere l'accesso alla
fotocamera. Un file index.html aperto direttamente dal filesystem non è una
prova affidabile.

PERSONALIZZAZIONE
Sostituisci reeko-overlay.png con un tuo PNG trasparente mantenendo lo stesso nome.
Nel file index.html puoi cambiare:
- URL CTA: cerca https://www.reeko.co/
- Testo CTA: cerca “Scopri Reeko”
- scala: scale="1.35 1.35 1.35"
- velocità float: dur:1500
- velocità pulse: dur:2200

Questa demo usa il marker Hiro integrato in AR.js per avere un test universale
senza dover generare un marker personalizzato.
