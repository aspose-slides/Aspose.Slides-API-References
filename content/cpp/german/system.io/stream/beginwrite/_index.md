---
title: BeginWrite()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Schreiboperation.
type: docs
weight: 170
url: /de/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) Methode

Startet eine asynchrone Schreiboperation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Puffer, der die zu schreibenden Daten enthält |
| offset | int | Ein nullbasierter Offset im **buffer**, der die Position angibt, ab der die zu schreibenden Daten beginnen |
| count | int | Die Anzahl der zu schreibenden Bytes |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Ein Rückruf, der aufgerufen wird, wenn die Operation abgeschlossen ist |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Schreiboperation eindeutig zu identifizieren |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die gestartete asynchrone Schreiboperation repräsentiert

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)