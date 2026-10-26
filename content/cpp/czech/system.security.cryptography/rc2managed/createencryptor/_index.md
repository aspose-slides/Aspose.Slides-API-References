---
title: CreateEncryptor()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří šifrovací objekt s explicitními parametry.
type: docs
weight: 1
url: /cs/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří šifrovací objekt s explicitními parametry.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Encryption key in byte array form. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initial value in byte array form. |

### Vrácená hodnota

Nově vytvořený šifrovací objekt.

## RC2Managed::CreateEncryptor() metoda

Vytvoří šifrovací objekt s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda

Vytvoří šifrovací objekt s parametry definovanými objektem algoritmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICryptoTransform](../../icryptotransform/)
* Třída [RC2Managed](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)