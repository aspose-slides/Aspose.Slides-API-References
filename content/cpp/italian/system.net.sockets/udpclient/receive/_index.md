---
title: Receive()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un datagramma inviato da un server.
type: docs
weight: 92
url: /it/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) metodo


Restituisce un datagramma inviato da un server.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Un [IPEndPoint](../../../system.net/ipendpoint/) che rappresenta l'host remoto da cui sono stati inviati i dati. |

### Valore di ritorno

Un array di byte a cui verranno assegnati i dati ricevuti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [UdpClient](../)
* Spazio dei nomi [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)