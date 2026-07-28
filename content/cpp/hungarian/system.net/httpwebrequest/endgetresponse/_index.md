---
title: EndGetResponse()
second_title: Aspose.Slides C++ API referenciája
description: Megvárja, amíg a megadott aszinkron kérés az erőforrásra befejeződik.
type: docs
weight: 508
url: /hu/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metódus

Megvárja, amíg a megadott aszinkron kérése az erőforrásra befejeződik.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron kérést képvisel az erőforrásra. |

### Visszatérési érték

A webes válasz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [WebResponse](../../webresponse/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [HttpWebRequest](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)