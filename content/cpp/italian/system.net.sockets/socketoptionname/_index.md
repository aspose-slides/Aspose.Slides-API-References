---
title: SocketOptionName
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce i nomi delle opzioni socket per la classe Socket.
type: docs
weight: 248
url: /it/system.net.sockets/socketoptionname/
---
## enum SocketOptionName

Definisce i nomi delle opzioni socket per la classe [Socket](../socket/).

```cpp
enum class SocketOptionName
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Debug | 1 | Registra informazioni di debug. |
| AcceptConnection | 2 | Indica se un socket è in ascolto per una connessione in ingresso. |
| ReuseAddress | 4 | Indica se un socket può essere associato all'indirizzo già in uso. |
| KeepAlive | 8 | Abilita i pacchetti 'Keep-Alive' per una connessione socket. |
| DontRoute | 16 | Indica se un pacchetto è inviato direttamente agli indirizzi dell'interfaccia. |
| Broadcast | 32 | Indica se un socket può inviare messaggi broadcast. |
| UseLoopback | 64 | Ignora l'hardware quando possibile. |
| Linger | 128 | Il sistema bloccherà il processo al tentativo di chiusura finché non sarà in grado di trasmettere i dati. |
| OutOfBandInline | 256 | Riceve dati out-of-band nel flusso dati normale. |
| DontLinger | n/a | Indica se un socket verrà chiuso senza linger. |
| ExclusiveAddressUse | n/a | Un socket utilizzerà l'indirizzo associato in modo esclusivo. |
| SendBuffer | 4097 | Specifica la dimensione del buffer di invio. |
| ReceiveBuffer | 4098 | Specifica la dimensione del buffer di ricezione. |
| SendLowWater | 4099 | Specifica la quantità minima di dati per le operazioni di invio. |
| ReceiveLowWater | 4100 | Specifica la quantità minima di dati per le operazioni di ricezione. |
| SendTimeout | 4101 | Specifica il timeout per le operazioni di invio sincrono. |
| ReceiveTimeout | 4102 | Specifica il timeout per le operazioni di ricezione sincrono. |
| Error | 4103 | Restituisce lo stato di errore e lo cancella. |
| Type | 4104 | Restituisce il tipo di socket. |
| ReuseUnicastPort | 12295 | Indica se il sistema deve differire l'allocazione della porta effimera per le connessioni in uscita. |
| MaxConnections | 2147483647 | Questa opzione non è supportata. Veniva usata per specificare la lunghezza massima della coda di ascolto. |
| IPOptions | 1 | Specifica l'opzione IP che deve essere inserita nei datagrammi in uscita. |
| HeaderIncluded | 2 | L'intestazione è inclusa nei datagrammi in uscita. |
| TypeOfService | 3 | Modifica il tipo di campo di servizio dell'intestazione IP. |
| IpTimeToLive | 4 | Il valore TTL (time to live) IP. |
| MulticastInterface | 9 | Imposta l'interfaccia per i pacchetti multicast in uscita. |
| MulticastTimeToLive | 10 | Il valore TTL (time to live) del multicast IP. |
| MulticastLoopback | 11 | Il loopback del multicast IP. |
| AddMembership | 12 | Aggiunge un'appartenenza a un gruppo IP. |
| DropMembership | 13 | Rimuove un'appartenenza a un gruppo IP. |
| DontFragment | 14 | Non frammentare i datagrammi IP. |
| AddSourceMembership | 15 | Unisciti al gruppo/fonte IP. |
| DropSourceMembership | 16 | Rimuovi il gruppo/fonte IP. |
| BlockSource | 17 | Blocca il gruppo/fonte IP. |
| UnblockSource | 18 | Sblocca il gruppo/fonte IP. |
| PacketInformation | 19 | Riceve informazioni sul pacchetto per IPv4. |
| HopLimit | 21 | Fornisce un intero contenente il conteggio HOP del pacchetto. |
| IPProtectionLevel | 23 | Abilita la restrizione di un socket IPv6 all'ambito specificato. |
| IPv6Only | 27 | Il socket è limitato a inviare e ricevere solo pacchetti IPv6. |
| NoDelay | 1 | Disabilita l'algoritmo Nagle per la coalescenza dei pacchetti di invio. |
| BsdUrgent | 2 | Utilizza i dati urgenti come definito in RFC-1222. |
| Expedited | 2 | Utilizza i dati accelerati come definito in RFC-1222. |
| NoChecksum | 1 | Invia i datagrammi UDP con il checksum impostato a zero. |
| ChecksumCoverage | 20 | Imposta o ottiene la copertura del checksum UDP. |
| UpdateAcceptContext | 28683 | Aggiorna un socket client con le stesse proprietà di un socket in ascolto. |
| UpdateConnectContext | 28688 | Aggiorna un socket client con le stesse proprietà di un socket in ascolto. |

## Vedi anche

* Spazio dei nomi [System::Net::Sockets](../)
* Libreria [Aspose.Slides](../../)