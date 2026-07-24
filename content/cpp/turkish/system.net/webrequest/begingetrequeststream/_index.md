---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API Referansı
description: Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.
type: docs
weight: 300
url: /tr/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metod

Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir callback. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Kullanıcı tarafından sağlanan ve her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan veri. |

### Dönüş Değeri

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [WebRequest](../)
* İsim Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)