---
title: CreateEncryptor()
second_title: Aspose.Slides för C++ API-referens
description: Skapar krypteringsobjekt med explicita parametrar.
type: docs
weight: 1
url: /sv/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Skapar krypteringsobjekt med explicita parametrar.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Krypteringsnyckel i bytearrayformat. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initieringsvärde i bytearrayformat. |

### Returvärde

Nytt krypteringsobjekt.

## RC2Managed::CreateEncryptor() metod

Skapar krypteringsobjekt med parametrar som definieras av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Skapar krypteringsobjekt med parametrar som definieras av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICryptoTransform](../../icryptotransform/)
* Klass [RC2Managed](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)