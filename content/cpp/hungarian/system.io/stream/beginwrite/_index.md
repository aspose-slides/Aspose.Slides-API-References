---
title: BeginWrite()
second_title: Aspose.Slides C++ API referencia
description: Elindít egy aszinkron írási műveletet.
type: docs
weight: 170
url: /hu/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metódus


Elindít egy aszinkron írási műveletet.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az írandó adatokat tartalmazó puffer |
| offset | int | 0-bázisú eltolás a **buffer**-ben, amely megadja a kezdő pozíciót az írandó adatoknál |
| count | int | Az írandó bájtok száma |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | A visszahívás, amely a művelet befejezésekor lesz meghívva |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Felhasználó által megadott adat, amely egyedileg azonosítja az egyes aszinkron írási műveleteket |

### Return Value

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron írási műveletet képviseli

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [Stream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)