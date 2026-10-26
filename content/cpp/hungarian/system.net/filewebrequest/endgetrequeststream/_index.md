---
title: EndGetRequestStream()
second_title: Aspose.Slides C++ API hivatkozás
description: Várja meg, amíg a megadott aszinkron művelet a stream lekéréséhez befejeződik.
type: docs
weight: 157
url: /hu/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metódus

Várja meg, amíg a megadott aszinkron művelet a stream lekéréséhez befejeződik.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet reprezentál a stream lekéréséhez. |

### Visszatérési érték

A stream az erőforráshoz írandó adatokhoz.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [FileWebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)