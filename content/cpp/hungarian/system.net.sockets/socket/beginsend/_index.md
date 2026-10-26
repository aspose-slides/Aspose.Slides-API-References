---
title: BeginSend()
second_title: Aspose.Slides C++ API referencia
description: Elindít egy aszinkron küldési műveletet.
type: docs
weight: 495
url: /hu/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron küldési műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Egy puffer az adatok olvasásához. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A bájtok száma a megadott tömbben, az 'offset' paramétertől kezdve. |
| socketFlags | [SocketFlags](../../socketflags/) | A küldés viselkedése. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor kerül meghívásra. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adat, amely egyedileg azonosítja az egyes aszinkron küldési műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely az elindított aszinkron küldési műveletet ábrázolja.

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