---
title: EndGetResponse()
second_title: Aspose.Slides for C++ – Dokumentacja referencyjna API
description: Czeka, aż określone asynchroniczne żądanie zasobu zostanie zakończone.
type: docs
weight: 508
url: /pl/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metoda

Czeka, aż określone asynchroniczne żądanie zasobu zostanie zakończone.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący asynchroniczne żądanie zasobu. |

### Wartość zwracana

Odpowiedź sieciowa.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [WebResponse](../../webresponse/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [HttpWebRequest](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)