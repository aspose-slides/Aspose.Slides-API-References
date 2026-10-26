---
title: EndGetResponse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Čeká, dokud se nedokončí zadaný asynchronní požadavek na zdroj.
type: docs
weight: 508
url: /cs/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud se nedokončí zadaný asynchronní požadavek na zdroj.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní požadavek na zdroj. |

### Návratová hodnota

Webová odpověď.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [WebResponse](../../webresponse/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [HttpWebRequest](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)