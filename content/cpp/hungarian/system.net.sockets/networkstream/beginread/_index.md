---
title: BeginRead()
second_title: Aspose.Slides C++ API referencia
description: Elindít egy aszinkron olvasási műveletet.
type: docs
weight: 248
url: /hu/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron olvasási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájttömb, ahová az olvasott bájtok lesznek írva. |
| offset | **int32_t** | A megadott tömbben lévő bájtokban kifejezett eltolás. |
| size | **int32_t** | A beolvasandó bájtok száma. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Az a visszahívás, amelyet a művelet befejeződésekor hívnak meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által megadott adat, amely egyedileg azonosítja az egyes aszinkron olvasási műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron olvasási műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [NetworkStream](../)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)