---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API-referencia
description: Addig vár, amíg a megadott aszinkron kérés a forrásra befejeződik.
type: docs
weight: 287
url: /hu/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metódus


Addig vár, amíg a megadott aszinkron kérés a forrásra befejeződik.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron kérést képvisel a forrásra. |

### Visszatérési érték

A webválasz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [WebResponse](../../webresponse/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [WebRequest](../)
* Névtér [System::Net](../../)
* Library [Aspose.Slides](../../../)