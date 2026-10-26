---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API Referansı
description: Şifreleyici nesnesini açık parametrelerle oluşturur.
type: docs
weight: 1
url: /tr/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Belirtilen parametrelerle şifreleyici nesnesi oluşturur.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte dizi biçiminde şifreleme anahtarı. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte dizi biçiminde başlangıç değeri. |

### Dönüş Değeri

Yeni oluşturulan şifreleyici nesnesi.

## RC2Managed::CreateEncryptor() metod


Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../../icryptotransform/)
* Sınıf [RC2Managed](../)
* İsim alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)