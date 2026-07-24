---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API Referansı
description: Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.
type: docs
weight: 144
url: /tr/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metod

Kaynağa veri yazmak için bir akış elde etmeye yönelik asenkron bir işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan, kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## İlgili Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [FileWebRequest](../)
* Ad alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)