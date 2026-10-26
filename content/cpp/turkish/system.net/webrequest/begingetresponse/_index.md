---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API Referansı
description: Kaynak için asenkron bir isteği başlatır.
type: docs
weight: 274
url: /tr/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) yöntemi


Kaynak için asenkron bir isteği başlatır.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Kullanıcı tarafından sağlanan ve her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan veri. |

### Dönüş Değeri

Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, başlatılan asenkron işlemi temsil eder.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [WebRequest](../)
* Ad alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)