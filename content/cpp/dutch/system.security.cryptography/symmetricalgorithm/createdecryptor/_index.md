---
title: CreateDecryptor()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een decryptor met parameters die aan het algoritme-object zijn gekoppeld.
type: docs
weight: 196
url: /nl/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() methode

Maakt een decryptor met parameters die aan het algoritme-object zijn gekoppeld.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Retourwaarde

Nieuw aangemaakt decryptor-object.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) methode

Maakt een decryptor met expliciete parameters.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Te gebruiken sleutel. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initiële waarde om te gebruiken. |

### Retourwaarde

Nieuw aangemaakt decryptor-object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [SymmetricAlgorithm](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)