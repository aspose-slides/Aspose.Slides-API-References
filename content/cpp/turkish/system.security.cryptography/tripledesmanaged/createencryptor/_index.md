---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API Referansı
description: Şifreleyici nesnesini açık parametrelerle oluşturur.
type: docs
weight: 1
url: /tr/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metot

Şifreleyici nesnesini açık parametrelerle oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte dizi biçiminde şifreleme anahtarı. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte dizi biçiminde başlangıç değeri. |

### Dönüş Değeri

Yeni oluşturulan şifreleyici nesnesi.

## TripleDESManaged::CreateEncryptor() metot

Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metot

Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../../icryptotransform/)
* Sınıf [TripleDESManaged](../)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)