---
title: SocketError
second_title: Riferimento API Aspose.Slides per C++
description: Enumera i tipi di errore del socket.
type: docs
weight: 209
url: /it/system.net.sockets/socketerror/
---
## SocketError enum

Enumera i tipi di errore del socket.

```cpp
enum class SocketError
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Success | 0 | Un'operazione di socket è stata completata con successo. |
| SocketError | -1 | Si è verificato un errore di socket non specificato. |
| Interrupted | 10004 | Una chiamata di socket bloccante è annullata. |
| AccessDenied | 10013 | L'accesso a un socket è negato. |
| Fault | 10014 | È stato rilevato un indirizzo di puntatore non valido. |
| InvalidArgument | 10022 | È stato fornito un argomento non valido. |
| TooManyOpenSockets | 10024 | Ci sono troppi socket aperti nel provider di socket sottostante. |
| WouldBlock | 10035 | Un'operazione non può essere completata immediatamente su un socket non bloccante. |
| InProgress | 10036 | Un'operazione bloccante è in corso. |
| AlreadyInProgress | 10037 | Un socket non bloccante ha già un'operazione in esecuzione. |
| NotSocket | 10038 | Un tentativo di chiamare un'operazione di socket su un non-socket. |
| DestinationAddressRequired | 10039 | Un indirizzo richiesto è stato omesso da un'operazione di socket. |
| MessageSize | 10040 | Un datagramma è troppo lungo. |
| ProtocolType | 10041 | Questo socket non supporta un tipo di protocollo. |
| ProtocolOption | 10042 | È stata usata un'opzione o un livello sconosciuto, non valido o non supportato. |
| ProtocolNotSupported | 10043 | Un protocollo non è implementato o non è configurato. |
| SocketNotSupported | 10044 | Una famiglia di indirizzi non supporta il socket specificato. |
| OperationNotSupported | 10045 | Una famiglia di protocolli non supporta una famiglia di indirizzi. |
| ProtocolFamilyNotSupported | 10046 | Una famiglia di protocolli non è implementata o non è configurata. |
| AddressFamilyNotSupported | 10047 | La famiglia di indirizzi specificata non è supportata. |
| AddressAlreadyInUse | 10048 | Un indirizzo può essere usato solo una volta. |
| AddressNotAvailable | 10049 | L'indirizzo IP selezionato non è valido in questo contesto. |
| NetworkDown | 10050 | La rete non è disponibile. |
| NetworkUnreachable | 10051 | Non esiste alcun percorso per l'host remoto. |
| NetworkReset | 10052 | Un'applicazione ha provato a impostare 'Keep-Alive' su una connessione già scaduta. |
| ConnectionAborted | 10053 | Una connessione è interrotta. |
| ConnectionReset | 10054 | Una connessione è stata ripristinata da un peer remoto. |
| NoBufferSpaceAvailable | 10055 | Non è disponibile spazio buffer libero per un'operazione di socket. |
| IsConnected | 10056 | Un socket è già connesso. |
| NotConnected | 10057 | Un'applicazione ha provato a inviare o ricevere dati, ma un socket non è connesso. |
| Shutdown | 10058 | Una richiesta di inviare o ricevere dati è vietata perché il socket è già stato chiuso. |
| TimedOut | 10060 | Un tentativo di connessione è scaduto, o un host connesso non ha risposto. |
| ConnectionRefused | 10061 | Un host remoto sta rifiutando attivamente una connessione. |
| HostDown | 10064 | Un'operazione è fallita perché un host remoto è inattivo. |
| HostUnreachable | 10065 | Non esiste alcun percorso di rete per l'host specificato. |
| ProcessLimit | 10067 | Troppi processi stanno usando il provider di socket sottostante. |
| SystemNotReady | 10091 | Un sottosistema di rete non è disponibile. |
| VersionNotSupported | 10092 | Una versione del provider di socket sottostante è fuori dall'intervallo. |
| NotInitialized | 10093 | Il provider di socket sottostante non è inizializzato. |
| Disconnecting | 10101 | Un arresto graduale è in corso. |
| TypeNotFound | 10109 | La classe specificata non è stata trovata. |
| HostNotFound | 11001 | L'host specificato è sconosciuto. |
| TryAgain | 11002 | Il nome di un host non può essere risolto. |
| NoRecovery | 11003 | Un errore è irrecuperabile o il database richiesto non può essere trovato. |
| NoData | 11004 | Il nome o l'indirizzo IP richiesto non è stato trovato sul server dei nomi. |

## Vedi anche

* Spazio dei nomi [System::Net::Sockets](../)
* Libreria [Aspose.Slides](../../)