---
title: CreateDecryptor()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een decryptor-object met expliciete parameters.
type: docs
weight: 14
url: /nl/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Maakt een decryptor object met expliciete parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Encryptiesleutel in byte array vorm. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initiele waarde in byte array vorm. |

### Retourwaarde

Nieuw aangemaakt decryptor object.

## TripleDESManaged::CreateDecryptor() methode

Maakt een decryptor object met parameters gedefinieerd door het algoritme object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Maakt een decryptor object met parameters gedefinieerd door het algoritme object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)