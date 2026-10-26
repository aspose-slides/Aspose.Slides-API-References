---
title: CreateDecryptor()
second_title: Aspose.Slides için C++ API Referansı
description: Algoritma nesnesiyle ilişkili parametrelerle bir çözücü oluşturur.
type: docs
weight: 196
url: /tr/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() yöntemi

Algoritma nesnesiyle ilişkili parametrelerle çözücü oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Döndürme Değeri

Yeni oluşturulan çözücü nesnesi.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) yöntemi

Açık parametrelerle çözücü oluşturur.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kullanılacak anahtar. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kullanılacak başlangıç değeri. |

### Döndürme Değeri

Yeni oluşturulan çözücü nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../../icryptotransform/)
* Sınıf [SymmetricAlgorithm](../)
* Ad Alanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)