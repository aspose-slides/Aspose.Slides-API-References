---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API Referansı
description: Algoritma nesnesiyle ilişkili parametrelerle şifreleyici oluşturur.
type: docs
weight: 183
url: /tr/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() metod


Algoritma nesnesiyle ilişkili parametrelerle şifreleyici oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```


### Dönüş Değeri

Yeni oluşturulmuş şifreleyici nesnesi.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Açık parametrelerle şifreleyici oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kullanılacak anahtar. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kullanılacak başlangıç değeri. |

### Dönüş Değeri

Yeni oluşturulmuş şifreleyici nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../../icryptotransform/)
* Sınıf [SymmetricAlgorithm](../)
* AdAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)