---
title: CreateDecryptor()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en dekrypterare med parametrar som är associerade med algoritmobjektet.
type: docs
weight: 196
url: /sv/system.security.cryptography/symmetricalgalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() metod

Skapar en dekrypterare med parametrar som är associerade med algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Returvärde

Nytt dekrypteringsobjekt.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Skapar en dekrypterare med explicita parametrar.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Nyckel att använda. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initialt värde att använda. |

### Returvärde

Nytt dekrypteringsobjekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICryptoTransform](../../icryptotransform/)
* Klass [SymmetricAlgorithm](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)