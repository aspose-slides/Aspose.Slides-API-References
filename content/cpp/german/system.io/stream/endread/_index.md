---
title: EndRead()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Leseoperation abgeschlossen ist.
type: docs
weight: 183
url: /de/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) Methode


Wartet, bis die angegebene asynchrone Leseoperation abgeschlossen ist.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das eine asynchrone Leseoperation darstellt |

### Rückgabewert

Die Anzahl der Bytes, die während der von **asyncResult** dargestellten Leseoperation gelesen wurden

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)