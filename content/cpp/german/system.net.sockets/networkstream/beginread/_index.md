---
title: BeginRead()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet einen asynchronen Lesevorgang.
type: docs
weight: 248
url: /de/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet einen asynchronen Lesevorgang.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die gelesenen Bytes geschrieben werden. |
| offset | **int32_t** | Der Versatz in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der zu lesenden Bytes. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die zur eindeutigen Identifizierung jedes asynchronen Lesevorgangs verwendet werden. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das den initiierten asynchronen Lesevorgang darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [NetworkStream](../)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)