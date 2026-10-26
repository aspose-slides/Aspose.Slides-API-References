---
title: IsBypassed()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ana bilgisayar için proxy'nin kullanılmaması gerektiğini gösteren bir değer döndürür.
type: docs
weight: 40
url: /tr/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) metot

Belirtilen ana bilgisayar için proxy'nin kullanılmaması gerektiğini gösteren bir değer döndürür.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Kontrol edilecek ana bilgisayar URI'sı. |

### Dönüş Değeri

Proxy sunucusunun kullanılmaması gerektiğinde true, aksi takdirde false.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [IWebProxy](../)
* Ad Alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)