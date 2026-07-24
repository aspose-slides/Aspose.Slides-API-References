---
title: EndReceive()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Empfangsoperation abgeschlossen ist.
type: docs
weight: 534
url: /de/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) Methode


Wartet, bis die angegebene asynchrone Empfangsoperation abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) Methode


Wartet, bis die angegebene asynchrone Empfangsoperation abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Siehe auch

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Socket](../)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)