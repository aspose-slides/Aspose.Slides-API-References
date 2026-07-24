---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen parametrelerle bir decryptor nesnesi oluşturur.
type: docs
weight: 14
url: /tr/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) yöntemi

Belirtilen parametrelerle bir decryptor nesnesi oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Şifreleme anahtarı, bayt dizisi biçiminde. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Başlangıç değeri, bayt dizisi biçiminde. |

### Dönüş Değeri

Yeni oluşturulan decryptor nesnesi.

## TripleDESManaged::CreateDecryptor() yöntemi

Algoritma nesnesi tarafından tanımlanan parametrelerle bir decryptor nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) yöntemi

Algoritma nesnesi tarafından tanımlanan parametrelerle bir decryptor nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../../icryptotransform/)
* Sınıf [TripleDESManaged](../)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)