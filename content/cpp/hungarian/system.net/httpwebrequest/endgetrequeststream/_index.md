---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API Referenciája
description: Vár, amíg a megadott adatfolyam lekéréséhez tartozó aszinkron művelet befejeződik.
type: docs
weight: 482
url: /hu/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metódus

Vár, amíg a megadott aszinkron művelet, amely adatfolyamot kér, befejeződik.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet képvisel az adatfolyam lekéréséhez. |

### Visszatérési érték

Az adatfolyam az erőforrásba írandó adatokhoz.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [HttpWebRequest](../)
* Névterület [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)