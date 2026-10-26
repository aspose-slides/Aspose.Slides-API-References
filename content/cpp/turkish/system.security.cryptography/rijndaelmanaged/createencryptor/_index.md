---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API Referansı
description: Şifreleyici nesnesini açık parametrelerle oluşturur.
type: docs
weight: 1
url: /tr/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Şifreleyici nesnesini açık parametrelerle oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Şifreleme anahtarı bayt dizisi biçiminde. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | İlk değer bayt dizisi biçiminde. |

### Dönüş Değeri

Yeni oluşturulmuş şifreleyici nesnesi.

## RijndaelManaged::CreateEncryptor() metod

Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../../icryptotransform/)
* Sınıf [RijndaelManaged](../)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)