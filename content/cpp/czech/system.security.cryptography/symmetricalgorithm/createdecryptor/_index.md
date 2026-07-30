---
title: CreateDecryptor()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří dešifrovací objekt s parametry spojenými s objektem algoritmu.
type: docs
weight: 196
url: /cs/system.security.cryptography/symmetricalgalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() metoda

Vytvoří dešifrovací objekt s parametry spojenými s objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Návratová hodnota

Nově vytvořený dešifrovací objekt.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří dešifrovací objekt s explicitními parametry.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Klíč k použití. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Počáteční hodnota k použití. |

### Návratová hodnota

Nově vytvořený dešifrovací objekt.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)