---
title: VerifySignature()
second_title: Aspose.Slides için C++ API Referansı
description: Veri üzerindeki imzayı doğrular.
type: docs
weight: 27
url: /tr/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

Veri üzerindeki imzayı doğrular.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) **rgbSignature** ile imzalanmış. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Veri için doğrulanacak imza. |

### Dönüş Değeri

İmza kontrolü başarılıysa doğru, aksi takdirde yanlış.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) method

Veri üzerindeki imzayı doğrular. Henüz uygulanmadı.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Hashleme için kullanılacak algoritma. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Veri için doğrulanacak imza. |

### Dönüş Değeri

İmza kontrolü başarılıysa doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [AsymmetricSignatureDeformatter](../)
* Sınıf [HashAlgorithm](../../hashalgorithm/)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)