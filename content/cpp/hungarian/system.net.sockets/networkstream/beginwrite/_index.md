---
title: BeginWrite()
second_title: Aspose.Slides for C++ API Referencia
description: Elindít egy aszinkron írási műveletet.
type: docs
weight: 274
url: /hu/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Elindít egy aszinkron írási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Egy puffer, amely a írandó adatokat tartalmazza. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| size | **int32_t** | A írandó bájtok száma. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Visszahívás, amelyet a művelet befejezésekor hívnak meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által megadott adat, amelyet az egyes aszinkron írási műveletek egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron írási műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)