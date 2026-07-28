---
title: EndSend()
second_title: Aspose.Slides C++ API referencia
description: Várakozik, amíg a megadott aszinkron küldési művelet befejeződik.
type: docs
weight: 508
url: /hu/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Várakozik, amíg a megadott aszinkron küldési művelet befejeződik.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron küldési műveletet reprezentál. |

### Visszatérési érték

A küldött bájtok száma.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Várakozik, amíg a megadott aszinkron küldési művelet befejeződik.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron küldési műveletet reprezentál. |
| errorCode | [SocketError](../../socketerror/)\& | A kimeneti paraméter, amelybe a hiba kód kerül, ha a küldési művelet meghiúsul. |

### Visszatérési érték

A küldött bájtok száma.

## Lásd még

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Socket](../)
* Névtér [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)