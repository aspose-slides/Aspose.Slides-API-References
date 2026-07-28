---
title: BeginRead()
second_title: Aspose.Slides C++ API Referencia
description: Elindít egy aszinkron olvasási műveletet.
type: docs
weight: 157
url: /hu/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metódus

Elindít egy aszinkron olvasási műveletet.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Egy puffert, amibe olvasni kell |
| offset | int | 0-alapú eltolás a **buffer**-ben, amely a pozíciót jelzi, ahonnan a beolvasott adat írása kezdődik |
| count | int | A beolvasandó bájtok száma |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amely a művelet befejezésekor kerül meghívásra |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | A felhasználó által megadott adat, amely egyedileg azonosítja az egyes aszinkron olvasási műveleteket |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron olvasási műveletet képviseli

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [Stream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)