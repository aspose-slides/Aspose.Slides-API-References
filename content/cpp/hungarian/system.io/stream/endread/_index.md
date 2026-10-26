---
title: EndRead()
second_title: Aspose.Slides C++ API referencia
description: Várja meg, amíg a megadott aszinkron olvasási művelet befejeződik.
type: docs
weight: 183
url: /hu/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) metódus

Várja meg, amíg a megadott aszinkron olvasási művelet befejeződik.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron olvasási műveletet képvisel |

### Visszatérési érték

A **asyncResult** által képviselt olvasási művelet során beolvasott bájtok száma

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Stream](../)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)