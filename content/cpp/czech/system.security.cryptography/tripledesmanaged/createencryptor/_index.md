---
title: CreateEncryptor()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří šifrovací objekt s explicitními parametry.
type: docs
weight: 1
url: /cs/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří šifrovací objekt s explicitními parametry.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Šifrovací klíč ve formě pole bajtů. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Počáteční hodnota ve formě pole bajtů. |

### Návratová hodnota

Nově vytvořený šifrovací objekt.

## TripleDESManaged::CreateEncryptor() metoda

Vytvoří šifrovací objekt s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří šifrovací objekt s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICryptoTransform](../../icryptotransform/)
* Třída [TripleDESManaged](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)