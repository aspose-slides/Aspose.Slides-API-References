---
title: EndRead()
second_title: Aspose.Slides C++ API referencia
description: Vár, amíg a megadott aszinkron olvasási művelet befejeződik.
type: docs
weight: 261
url: /hu/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) metódus

Vár, amíg a megadott aszinkron olvasási művelet befejeződik.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron olvasási műveletet képvisel |

### Visszatérési érték

A **asyncResult** által képviselt olvasási művelet során beolvasott bájtok száma

## Lásd még

* Tipedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [NetworkStream](../)
* Névtér [System::Net::Sockets](../../)
* Könyvtár [Aspose.Slides](../../../)