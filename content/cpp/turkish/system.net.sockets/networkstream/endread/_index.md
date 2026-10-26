---
title: EndRead()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen eşzamansız okuma işlemi tamamlanana kadar bekler.
type: docs
weight: 261
url: /tr/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) metod


Belirtilen eşzamansız okuma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) nesnesi, bir eşzamansız okuma işlemini temsil eder |

### Dönüş Değeri

**asyncResult** tarafından temsil edilen okuma işlemi sırasında okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [NetworkStream](../)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)