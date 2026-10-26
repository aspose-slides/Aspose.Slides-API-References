---
title: BeginWrite()
second_title: Aspose.Slides für C++ API-Referenz
description: Initiiert eine asynchrone Schreiboperation.
type: docs
weight: 443
url: /de/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) Methode


Initiert eine asynchrone Schreiboperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| count | **int32_t** | Die Anzahl der zu schreibenden Bytes. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Rückruf, der nach Abschluss der Operation aufgerufen wird. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Schreiboperation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die initiierte asynchrone Schreiboperation repräsentiert.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [SslStream](../)
* Namensraum [System::Net::Security](../../)
* Bibliothek [Aspose.Slides](../../../)