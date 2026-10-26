---
title: WebExceptionStatus
second_title: Riferimento API Aspose.Slides per C++
description: Elenca i codici di stato della classe WebException.
type: docs
weight: 651
url: /it/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Elenca i codici di stato della classe WebException.

```cpp
enum class WebExceptionStatus
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Success | 0 | Nessun errore si è verificato. |
| NameResolutionFailure | 1 | Il servizio di risoluzione dei nomi non è riuscito a risolvere il nome host. |
| ConnectFailure | 2 | Il punto di servizio remoto non è stato contattato a livello di trasporto. |
| ReceiveFailure | 3 | Una risposta completa non è stata ricevuta dal server remoto. |
| SendFailure | 4 | Una richiesta completa non è stata inviata al server remoto. |
| PipelineFailure | 5 | La richiesta era una richiesta pipeline e la connessione è stata chiusa prima che la risposta fosse ricevuta. |
| RequestCanceled | 6 | La richiesta è stata annullata o si è verificato un errore non classificabile. |
| ProtocolError | 7 | La risposta ricevuta dal server era completa ma indicava un errore a livello di protocollo. |
| ConnectionClosed | 8 | La connessione è stata chiusa prematuramente. |
| TrustFailure | 9 | Un certificato del server non è potuto essere convalidato. |
| SecureChannelFailure | 10 | Si è verificato un errore durante l'instaurazione di una connessione tramite SSL. |
| ServerProtocolViolation | 11 | La risposta del server non era una risposta HTTP valida. |
| KeepAliveFailure | 12 | La connessione per una richiesta che specifica l'intestazione 'Keep-Alive' è stata chiusa inaspettatamente. |
| Pending | 13 | Una richiesta asincrona interna è in sospeso. |
| Timeout | 14 | Non è stata ricevuta alcuna risposta durante il periodo di timeout per una richiesta. |
| ProxyNameResolutionFailure | 15 | Il servizio di risoluzione dei nomi non è riuscito a risolvere il nome host del proxy. |
| UnknownError | 16 | Si è verificata un'eccezione di tipo sconosciuto. |
| MessageLengthLimitExceeded | 17 | È stato ricevuto un messaggio che superava il limite specificato. |
| CacheEntryNotFound | 18 | La voce di cache specificata non è stata trovata. |
| RequestProhibitedByCachePolicy | 19 | La richiesta non era consentita dalla politica della cache. |
| RequestProhibitedByProxy | 20 | Questa richiesta non era consentita dal proxy. |

## Vedi anche

* Spazio dei nomi [System::Net](../)
* Libreria [Aspose.Slides](../../)