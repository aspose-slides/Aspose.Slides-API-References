---
title: EndRead()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Leseoperation abgeschlossen ist.
type: docs
weight: 261
url: /de/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) Methode


Wartet, bis die angegebene asynchrone Leseoperation abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Leseoperation darstellt |

### Rückgabewert

Die Anzahl der Bytes, die während der von **asyncResult** dargestellten Leseoperation gelesen wurden

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [NetworkStream](../)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)