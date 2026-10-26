---
title: EndRead()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen eşzamanlı okuma işlemi tamamlanana kadar bekler.
type: docs
weight: 430
url: /tr/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) yöntemi

Belirtilen eşzamanlı okuma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Bir [IAsyncResult](../../../system/iasyncresult/) nesnesi, bir eşzamanlı okuma işlemini temsil eder |

### Dönüş Değeri

**asyncResult** tarafından temsil edilen okuma işlemi sırasında okunan bayt sayısı

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [SslStream](../)
* Ad Alanı [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)