---
title: CreateSignature()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri için imzayı oluşturur.
type: docs
weight: 1
url: /tr/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) yöntemi

Belirtilen veri için imzayı oluşturur.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) hash hesaplamak için. |

### Dönüş Değeri

Bayt dizisi biçiminde hesaplanmış imza.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) yöntemi

Belirtilen hash değeri için imzayı oluşturur.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | İmza oluştururken kullanılacak hash algoritması. |

### Dönüş Değeri

Bayt dizisi biçiminde hesaplanmış imza.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [AsymmetricSignatureFormatter](../)
* Sınıf [HashAlgorithm](../../hashalgorithm/)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)