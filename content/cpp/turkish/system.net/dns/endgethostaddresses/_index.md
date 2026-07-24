---
title: EndGetHostAddresses()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen asenkron işlemin yeni bir IPHostEntry-class örneği oluşturmasını tamamlayana kadar bekler.
type: docs
weight: 144
url: /tr/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) yöntemi

Belirtilen asenkron işlemin yeni bir IPHostEntry-class örneği oluşturmasını tamamlayana kadar bekler.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Asenkron bir işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |

### Dönüş Değeri

Yeni oluşturulmuş bir IPHostEntry-class örneği.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPAddress](../../ipaddress/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Dns](../)
* İsim Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)