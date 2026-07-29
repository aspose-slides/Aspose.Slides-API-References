---
title: CreateDecryptor()
second_title: Aspose.Slides för C++ API-referens
description: Skapar avkrypteringsobjekt med explicita parametrar.
type: docs
weight: 14
url: /sv/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Skapar avkrypteringsobjekt med explicita parametrar.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Krypteringsnyckel i byte-arrayformat. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initialvärde i byte-arrayformat. |

### Returvärde

Nyligen skapat avkrypteringsobjekt.

## RC2Managed::CreateDecryptor() metod


Skapar avkrypteringsobjekt med parametrar definierade av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod


Skapar avkrypteringsobjekt med parametrar definierade av algoritmobjektet.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICryptoTransform](../../icryptotransform/)
* Klass [RC2Managed](../)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)