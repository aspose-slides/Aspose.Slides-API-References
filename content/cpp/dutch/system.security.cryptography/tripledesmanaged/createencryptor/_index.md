---
title: CreateEncryptor()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een encryptor-object met expliciete parameters.
type: docs
weight: 1
url: /nl/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Maakt een encryptor-object met expliciete parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Encryptiesleutel in byte-arrayvorm. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Beginwaarde in byte-arrayvorm. |

### Retourwaarde

Nieuw aangemaakt encryptor-object.

## TripleDESManaged::CreateEncryptor() methode

Maakt een encryptor-object met parameters die door het algoritme-object worden gedefinieerd.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Maakt een encryptor-object met parameters die door het algoritme-object worden gedefinieerd.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)