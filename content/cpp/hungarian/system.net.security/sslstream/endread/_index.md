---
title: EndRead()
second_title: Aspose.Slides C++ API referencia
description: Megvárja, amíg a megadott aszinkron olvasási művelet befejeződik.
type: docs
weight: 430
url: /hu/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) metódus

Megvárja, amíg a megadott aszinkron olvasási művelet befejeződik.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron olvasási műveletet képvisel |

### Return Value

A **asyncResult** által képviselt olvasási művelet során beolvasott bájtok száma

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [SslStream](../)
* Névtér [System::Net::Security](../../)
* Könyvtár [Aspose.Slides](../../../)