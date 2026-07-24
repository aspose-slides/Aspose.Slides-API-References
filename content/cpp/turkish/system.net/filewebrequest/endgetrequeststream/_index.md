---
title: EndGetRequestStream()
second_title: C++ için Aspose.Slides API Referansı
description: Akış elde etmek için belirtilen asenkron işlemin tamamlanmasını bekler.
type: docs
weight: 157
url: /tr/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) yöntem

Belirtilen akış elde etme asenkron işlemi tamamlanana kadar bekler.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, akış elde etmek için bir asenkron işlemi temsil eder. |

### Dönüş Değeri

Kaynağa veri yazmak için kullanılan akış.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [FileWebRequest](../)
* İsim Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)