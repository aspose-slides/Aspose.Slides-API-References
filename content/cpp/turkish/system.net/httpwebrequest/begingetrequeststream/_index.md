---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API Referansı
description: Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.
type: docs
weight: 469
url: /tr/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) yöntemi

Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan, kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [HttpWebRequest](../)
* Ad alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)