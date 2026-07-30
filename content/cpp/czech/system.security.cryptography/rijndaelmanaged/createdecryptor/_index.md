---
title: CreateDecryptor()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří dešifrovací objekt s explicitními parametry.
type: docs
weight: 14
url: /cs/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Vytvoří dešifrovací objekt s explicitními parametry.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Šifrovací klíč ve formě pole bajtů. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Počáteční hodnota ve formě pole bajtů. |

### Návratová hodnota

Nově vytvořený dešifrovací objekt.

## RijndaelManaged::CreateDecryptor() metoda


Vytvoří dešifrovací objekt s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Vytvoří dešifrovací objekt s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICryptoTransform](../../icryptotransform/)
* Třída [RijndaelManaged](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)