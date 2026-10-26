---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen akışı elde etmek için asenkron işlemin tamamlanmasını bekler.
type: docs
weight: 482
url: /tr/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metot


Belirtilen akışı elde etme asenkron bir işlemi tamamlanana kadar bekler.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Akış elde etme asenkron bir işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |

### Dönüş Değeri

Kaynağa veri yazmak için kullanılan akış.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [HttpWebRequest](../)
* İsim alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)