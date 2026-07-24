---
title: CreateDecryptor()
second_title: Aspose.Slides için C++ API Referansı
description: Açık parametrelerle şifre çözücü nesnesi oluşturur.
type: docs
weight: 14
url: /tr/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metot


Açık parametrelerle şifre çözücü nesnesi oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Şifreleme anahtarı bayt dizisi biçiminde. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | İlk değer bayt dizisi biçiminde. |

### Dönüş Değeri

Yeni oluşturulan şifre çözücü nesnesi.

## RijndaelManaged::CreateDecryptor() metot


Algoritma nesnesi tarafından tanımlanan parametrelerle şifre çözücü nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metot


Algoritma nesnesi tarafından tanımlanan parametrelerle şifre çözücü nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)