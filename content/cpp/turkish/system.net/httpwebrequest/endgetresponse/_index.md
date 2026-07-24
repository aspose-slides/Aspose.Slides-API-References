---
title: EndGetResponse()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen kaynağa yönelik eşzamansız isteğin tamamlanmasını bekler.
type: docs
weight: 508
url: /tr/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metot

Belirtilen kaynak için eşzamansız isteğin tamamlanmasını bekler.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) nesnesi, kaynak için bir eşzamansız isteği temsil eder. |

### Dönüş Değeri

Web yanıtı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [WebResponse](../../webresponse/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [HttpWebRequest](../)
* İsim Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)