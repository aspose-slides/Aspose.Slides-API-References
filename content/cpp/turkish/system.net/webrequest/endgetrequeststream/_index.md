---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen akışı elde etmek için asenkron işlemin tamamlanmasını bekler.
type: docs
weight: 313
url: /tr/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) yöntemi

Belirtilen asenkron akış alma işlemi tamamlanana kadar bekler.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi; akış elde etmek için asenkron bir işlemi temsil eder. |

### Dönüş Değeri

Kaynağa veri yazmak için kullanılan akış.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [WebRequest](../)
* Ad Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)