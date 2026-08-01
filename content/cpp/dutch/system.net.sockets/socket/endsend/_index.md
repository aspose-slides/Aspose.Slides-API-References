---
title: EndSend()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de opgegeven asynchrone verzendbewerking is voltooid.
type: docs
weight: 508
url: /nl/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) methode


Wacht tot de opgegeven asynchrone verzendbewerking is voltooid.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone verzendbewerking vertegenwoordigt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) methode


Wacht tot de opgegeven asynchrone verzendbewerking is voltooid.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone verzendbewerking vertegenwoordigt. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de verzendbewerking mislukt. |

### Retourwaarde

Het aantal verzonden bytes.

## Zie ook

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Socket](../)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)