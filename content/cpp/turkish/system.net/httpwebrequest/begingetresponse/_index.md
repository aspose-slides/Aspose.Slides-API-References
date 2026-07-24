---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API Referansı
description: Kaynak için asenkron bir isteği başlatır.
type: docs
weight: 495
url: /tr/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metot

Kaynak için asenkron bir isteği başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Kullanıcı tarafından sağlanan ve her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan veri. |

### Dönüş Değeri

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [HttpWebRequest](../)
* Ad alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)