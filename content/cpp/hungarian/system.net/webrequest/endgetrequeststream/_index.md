---
title: EndGetRequestStream()
second_title: Aspose.Slides C++ API hivatkozás
description: Megvárja, amíg a megadott aszinkron művelet a stream lekérése befejeződik.
type: docs
weight: 313
url: /hu/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metódus

Vár, amíg a megadott aszinkron művelet a stream lekérésére befejeződik.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet képvisel a stream lekéréséhez. |

### Visszatérési érték

A stream az erőforrásba írandó adatokhoz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [WebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)