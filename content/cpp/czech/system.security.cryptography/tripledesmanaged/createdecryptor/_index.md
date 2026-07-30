---
title: CreateDecryptor()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří objekt dekriptoru s explicitními parametry.
type: docs
weight: 14
url: /cs/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří objekt dekriptoru s explicitními parametry.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Šifrovací klíč v podobě pole bajtů. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Počáteční hodnota v podobě pole bajtů. |

### Vrácená hodnota

Nově vytvořený objekt dekriptoru.

## TripleDESManaged::CreateDecryptor() metoda

Vytvoří objekt dekriptoru s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří objekt dekriptoru s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICryptoTransform](../../icryptotransform/)
* Třída [TripleDESManaged](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)