---
title: BeginRead()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Leseoperation.
type: docs
weight: 157
url: /de/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) Methode

Startet eine asynchrone Leseoperation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Puffer zum Lesen |
| offset | int | Ein 0-basierter Versatz in **buffer**, der die Position angibt, ab der die gelesenen Daten geschrieben werden sollen |
| count | int | Die Anzahl der zu lesenden Bytes |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Ein Callback, der aufgerufen wird, wenn die Operation abgeschlossen ist |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Leseoperation eindeutig zu identifizieren |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die gestartete asynchrone Leseoperation darstellt

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)