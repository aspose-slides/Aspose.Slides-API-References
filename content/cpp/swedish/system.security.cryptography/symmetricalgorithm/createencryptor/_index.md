---
title: CreateEncryptor()
second_title: Aspose.Slides för C++ API-referens
description: Skapar krypterare med parametrar som är associerade med algoritmobjektet.
type: docs
weight: 183
url: /sv/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() metod


Skapar krypterare med parametrar som är associerade med algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```


### Returvärde

Nytt skapat krypteringsobjekt.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Skapar krypterare med explicita parametrar.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Nyckel att använda. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initialt värde att använda. |

### Returvärde

Nytt skapat krypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICryptoTransform](../../icryptotransform/)
* Klass [SymmetricAlgorithm](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)