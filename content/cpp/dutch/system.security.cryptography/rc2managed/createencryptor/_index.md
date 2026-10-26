---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API-referentie
description: Maakt encryptor-object met expliciete parameters.
type: docs
weight: 1
url: /nl/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Maakt encryptor-object met expliciete parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Encryptiesleutel in bytearrayvorm. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Beginwaarde in bytearrayvorm. |

### Retourwaarde

Nieuw aangemaakt encryptor-object.

## RC2Managed::CreateEncryptor() method


Maakt encryptor-object met parameters gedefinieerd door het algoritmeobject.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Maakt encryptor-object met parameters gedefinieerd door het algoritmeobject.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [RC2Managed](../)
* Naamruimte [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)