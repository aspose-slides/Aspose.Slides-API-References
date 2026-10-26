---
title: EndGetHostByName()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen asenkron işlemin yeni bir IPHostEntry-class örneği oluşturulmasını tamamlayana kadar bekler.
type: docs
weight: 66
url: /tr/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) metodu

Belirtilen asenkron işlemin yeni IPHostEntry-class örneği oluşturulmasını bekler.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Asenkron bir işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |

### Dönüş Değeri

Yeni oluşturulmuş bir IPHostEntry-class örneği.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPHostEntry](../../iphostentry/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Dns](../)
* Ad alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)