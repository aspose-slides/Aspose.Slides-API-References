---
title: BeginWrite()
second_title: Aspose.Slides für C++ API-Referenz
description: Initiert einen asynchronen Schreibvorgang.
type: docs
weight: 274
url: /de/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode

Initiert einen asynchronen Schreibvorgang.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Puffer, der die zu schreibenden Daten enthält. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der zu schreibenden Bytes. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerdaten, die verwendet werden, um jede asynchrone Schreiboperation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die initiierte asynchrone Schreiboperation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [NetworkStream](../)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)