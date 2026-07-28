---
title: EndReceive()
second_title: Aspose.Slides a C++ API referencia
description: Vár, amíg a megadott aszinkron fogadási művelet befejeződik.
type: docs
weight: 534
url: /hu/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) metódus


Vár, amíg a megadott aszinkron fogadási művelet befejeződik.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |

### Visszatérési érték

A fogadott bájtok száma.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) metódus


Vár, amíg a megadott aszinkron fogadási művelet befejeződik.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Visszatérési érték

A fogadott bájtok száma.

## Lásd még

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Socket](../)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)