---
title: IOControlCode
second_title: Riferimento API di Aspose.Slides per C++
description: Elenca i codici di controllo IO.
type: docs
weight: 157
url: /it/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

Elenca i codici di controllo [IO](../../system.io/).

```cpp
enum class IOControlCode : int64_t
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AsyncIO | -2147195267 | Abilita o disabilita la modalità I/O asincrona del socket. |
| NonBlockingIO | -2147195266 | Imposta il socket come non bloccante. |
| DataToRead | 1074030207 | Restituisce il numero di byte disponibili per la lettura. |
| OobDataRead | 1074033415 | Restituisce informazioni sui dati out-of-band in attesa di essere ricevuti. |
| AssociateHandle | -2013265919 | Associa questo socket al handle specificato di un'interfaccia complementare. |
| EnableCircularQueuing | 671088642 | Sostituisce il datagramma più vecchio nella coda con uno in arrivo quando le code dei messaggi in arrivo sono piene. |
| Flush | 671088644 | Scarta il contenuto corrente della coda di invio associata a questo socket. |
| GetBroadcastAddress | 1207959557 | Restituisce una struttura SOCKADDR che contiene l'indirizzo broadcast per la famiglia di indirizzi del socket corrente. |
| GetExtensionFunctionPointer | -939524090 | Recupera un puntatore alla funzione di estensione specificata supportata dal service provider associato. |
| GetQos | -939524089 | Recupera la struttura QOS associata al socket. |
| GetGroupQos | -939524088 | Restituisce gli attributi QOS per il gruppo di socket. |
| MultipointLoopback | -2013265911 | Controlla se i dati inviati da un'applicazione sul computer locale (non necessariamente dallo stesso socket) in una sessione multicast saranno ricevuti da un socket unito al gruppo di destinazione multicast sull'interfaccia di loopback. |
| MulticastScope | -2013265910 | Controlla il numero di volte in cui un pacchetto multicast può essere inoltrato da un router, noto anche come TTL o conteggio dei hop. |
| SetQos | -2013265909 | Imposta gli attributi QOS per il socket. |
| SetGroupQos | -2013265908 | Imposta gli attributi QOS per il gruppo di socket. |
| TranslateHandle | -939524083 | Restituisce un handle per il socket valido nel contesto di un'interfaccia complementare. |
| RoutingInterfaceQuery | -939524076 | Restituisce gli indirizzi di interfaccia che possono essere usati per connettersi all'indirizzo remoto specificato. |
| RoutingInterfaceChange | -2013265899 | Abilita la ricezione di una notifica quando l'interfaccia locale usata per accedere a un endpoint remoto cambia. |
| AddressListQuery | 1207959574 | Restituisce l'elenco delle interfacce locali a cui il socket può associarsi. |
| AddressListChange | 671088663 | Abilita la ricezione di una notifica quando l'elenco delle interfacce locali per la famiglia di protocolli del socket cambia. |
| QueryTargetPnpHandle | 1207959576 | Recupera l'handle SOCKET del provider sottostante. |
| NamespaceChange | -2013265895 | Controlla se il socket riceve notifiche quando una query di namespace diventa non valida. |
| AddressListSort | -939524071 | Ordina un elenco di indirizzi di destinazione IPv6 e IPv4 per determinare il miglior indirizzo disponibile per stabilire una connessione. |
| ReceiveAll | -1744830463 | Abilita la ricezione di tutti i pacchetti IPv4 sulla rete. |
| ReceiveAllMulticast | -1744830462 | Abilita la ricezione di tutti i pacchetti IPv4 multicast sulla rete. |
| ReceiveAllIgmpMulticast | -1744830461 | Abilita la ricezione di tutti i pacchetti IGMP sulla rete. |
| KeepAliveValues | -1744830460 | Controlla l'invio di pacchetti TCP keep-alive e l'intervallo con cui vengono inviati. |
| AbsorbRouterAlert | -1744830459 | Questo valore è uguale alla costante 'SIO_ABSORB_RTRALERT' di Winsock 2. |
| UnicastInterface | -1744830458 | Imposta l'interfaccia usata per i pacchetti unicast in uscita. |
| LimitBroadcasts | -1744830457 | Questo valore è uguale alla costante 'SIO_LIMIT_BROADCASTS' di Winsock 2. |
| BindToInterface | -1744830456 | Associa il socket a un indice di interfaccia specificato. |
| MulticastInterface | -1744830455 | Imposta l'interfaccia usata per i pacchetti multicast in uscita. |
| AddMulticastGroupOnInterface | -1744830454 | Unisciti a un gruppo multicast usando un'interfaccia identificata dal suo indice. |
| DeleteMulticastGroupFromInterface | -1744830453 | Rimuove il socket da un gruppo multicast. |

## Vedi anche

* Spazio dei nomi [System::Net::Sockets](../)
* Libreria [Aspose.Slides](../../)