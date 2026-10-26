---
title: EndReceive()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de opgegeven asynchrone ontvangoperatie is voltooid.
type: docs
weight: 534
url: /nl/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) methode


Wacht tot de opgegeven asynchrone ontvangoperatie is voltooid.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone ontvangoperatie vertegenwoordigt. |

### Returnwaarde

Het aantal bytes dat wordt ontvangen.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) methode


Wacht tot de opgegeven asynchrone ontvangoperatie is voltooid.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone ontvangoperatie vertegenwoordigt. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de ontvangoperatie mislukt. |

### Returnwaarde

Het aantal ontvangen bytes.

## Zie ook

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)