---
title: BeginReceive()
second_title: Aspose.Slides C++ API Referencia
description: Aszinkron írási műveletet indít el.
type: docs
weight: 521
url: /hu/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron írási műveletet indít el.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a fogadott adat kerül. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A bájtok száma a megadott tömbben az 'offset' paramétertől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A fogadási viselkedés. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejezésekor hívnak meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által megadott adatok, amelyeket az egyes aszinkron fogadási műveletek egyedi azonosítására használnak. |

### Visszatérési érték

[IAsyncResult](../../../system/iasyncresult/) objektum, amely az indított aszinkron fogadási műveletet képviseli.

## Lásd még

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [Socket](../)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)