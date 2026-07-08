# Informativa sulla Privacy — Φάρος (Pharos)

**Ultimo aggiornamento:** 8 luglio 2026

## Chi siamo

Φάρος (Pharos) è un'applicazione Android gratuita, open source e senza pubblicità, sviluppata da Gilberto Odino Pasquariello ("lo Sviluppatore"). Il codice sorgente completo è pubblicamente disponibile e verificabile su GitHub: [github.com/odino-pharos/pharos](https://github.com/odino-pharos/pharos).

Questa informativa spiega in modo chiaro e completo come Pharos tratta i dati durante il suo utilizzo.

## Il principio fondamentale

**Pharos non raccoglie, non trasmette e non condivide alcun dato personale con lo Sviluppatore o con terze parti.** Tutti i dati generati dall'app restano esclusivamente memorizzati sul dispositivo dell'utente, nella memoria locale dell'applicazione. Nessun server esterno riceve mai informazioni da Pharos.

## Dati trattati dall'app e dove restano

### Posizione GPS
Pharos utilizza la posizione GPS del dispositivo (inclusa in background, quando l'app non è in primo piano) per rilevare la velocità di movimento e determinare quando attivare o disattivare il blocco dei dati mobili. **Le coordinate di posizione vengono elaborate esclusivamente in tempo reale sul dispositivo e non vengono mai salvate, registrate, trasmesse o condivise in alcuna forma.** Non esiste alcuna cronologia dei percorsi GPS accessibile né dallo Sviluppatore né da terzi.

### Sessioni di guida
Al termine di ogni sessione di guida, l'app salva localmente (tramite lo storage privato dell'applicazione sul dispositivo) alcune informazioni riassuntive: durata del tragitto, chilometri percorsi, orario di inizio e fine. Questi dati:
- restano esclusivamente sul dispositivo dell'utente;
- non vengono mai sincronizzati, esportati automaticamente o inviati a server esterni;
- sono cancellabili in qualsiasi momento dall'utente disinstallando l'app o cancellando i dati dell'app dalle impostazioni di sistema Android.

### Funzione VPN locale
Pharos utilizza l'API VpnService di Android per bloccare selettivamente il traffico dati di alcune applicazioni durante la guida (ad eccezione di app di navigazione e musica, che restano attive). Questa funzione **opera interamente in locale sul dispositivo**: non instrada, non intercetta, non registra e non trasmette alcun traffico di rete verso server dello Sviluppatore o di terze parti. Pharos non è una VPN nel senso tradizionale (non nasconde né instrada la connessione altrove) — utilizza semplicemente l'API di sistema Android per bloccare pacchetti dati in modo selettivo sul dispositivo stesso.

## Permessi richiesti dall'app

| Permesso | Finalità | Dati inviati a server esterni |
|---|---|---|
| Posizione (precisa/approssimativa/in background) | Rilevare la velocità di movimento | Nessuno |
| Servizio in primo piano (localizzazione) | Mantenere attivo il monitoraggio GPS durante la guida | Nessuno |
| Notifiche | Mostrare lo stato di Pharos durante la guida | Nessuno |
| Vibrazione | Segnalare eventi tramite feedback tattile | Nessuno |
| Avvio automatico al riavvio | Permettere il funzionamento continuo dopo un riavvio del telefono | Nessuno |
| Esclusione ottimizzazione batteria | Evitare che il sistema interrompa Pharos durante la guida | Nessuno |
| Accesso VPN locale | Bloccare selettivamente i dati mobili come descritto sopra | Nessuno |
| Internet | Riservato a eventuali funzionalità future (es. verifica aggiornamenti); attualmente inutilizzato per la trasmissione di dati personali | Nessuno attualmente |

Pharos **non richiede** l'accesso a contatti, fotocamera, microfono, SMS, file personali o account Google.

## Servizi di terze parti

Pharos **non integra alcun SDK di terze parti**: nessun servizio di analisi (analytics), nessun sistema di crash reporting, nessuna pubblicità, nessun tracciamento pubblicitario, nessuna raccolta statistiche di utilizzo. L'elenco completo delle librerie utilizzate è pubblicamente consultabile nel file `pubspec.yaml` del repository GitHub.

## Account utente

Pharos **non richiede alcuna registrazione, login o account** per funzionare. L'app è utilizzabile immediatamente dopo l'installazione, senza fornire alcun dato identificativo.

## Donazioni

Pharos offre facoltativamente la possibilità di sostenere il progetto tramite Ko-fi o PayPal. Queste transazioni avvengono interamente sulle piattaforme esterne Ko-fi e PayPal, secondo le rispettive informative sulla privacy; Pharos non riceve né elabora alcun dato di pagamento.

## Minori

Pharos non è rivolta specificamente a minori e non raccoglie consapevolmente dati di minori, in coerenza con il fatto che l'app non raccoglie dati di alcun utente.

## Diritti dell'utente (GDPR)

Poiché Pharos non raccoglie né conserva alcun dato personale su server esterni, non esistono dati dello Sviluppatore su cui esercitare diritti di accesso, rettifica o cancellazione: **l'utente ha già il pieno controllo dei propri dati**, che risiedono unicamente sul proprio dispositivo. La disinstallazione dell'app o la cancellazione dei dati dalle impostazioni Android rimuove definitivamente ogni informazione generata da Pharos.

## Modifiche a questa informativa

Questa informativa potrà essere aggiornata in futuro, ad esempio in caso di nuove funzionalità. Eventuali modifiche saranno pubblicate su questa stessa pagina, con indicazione della data di ultimo aggiornamento in cima al documento.

## Contatti

Per qualsiasi domanda relativa a questa informativa o al trattamento dei dati, è possibile contattare lo Sviluppatore tramite il repository GitHub del progetto: [github.com/odino-pharos/pharos](https://github.com/odino-pharos/pharos).
