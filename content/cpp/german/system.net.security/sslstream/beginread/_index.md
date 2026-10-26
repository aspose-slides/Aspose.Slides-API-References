---
title: BeginRead()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet einen asynchronen Lesevorgang.
type: docs
weight: 417
url: /de/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet einen asynchronen Lesevorgang.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, aus dem Daten gelesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn die Operation abgeschlossen ist. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die zur eindeutigen Identifizierung jeder asynchronen Leseoperation verwendet werden. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die gestartete asynchrone Leseoperation darstellt.

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)