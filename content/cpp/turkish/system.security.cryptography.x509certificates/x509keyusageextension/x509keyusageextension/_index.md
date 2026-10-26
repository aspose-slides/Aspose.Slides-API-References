---
title: X509KeyUsageExtension()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan yapıcı.
type: docs
weight: 1
url: /tr/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() yapıcı


Varsayılan yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Anahtar kullanımının kodlanmış verileri. |
| critical | **bool** | Kritiklik işareti. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Anahtar kullanımları. |
| critical | **bool** | Kritiklik işareti. |

## Ayrıca Bakınız

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [X509KeyUsageExtension](../)
* Sınıf [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* AdAlanı [System::Security::Cryptography::X509Certificates](../../)
* Kütüphane [Aspose.Slides](../../../)