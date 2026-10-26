---
title: CreateSignature()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée la signature pour les données spécifiées.
type: docs
weight: 1
url: /fr/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) méthode


Crée la signature pour les données spécifiées.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) à calculer le hachage pour. |

### Valeur de retour

Signature calculée sous forme de tableau d'octets.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) méthode


Crée la signature pour la valeur de hachage spécifiée.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algorithme de hachage à utiliser lors de la création de la signature. |

### Valeur de retour

Signature calculée sous forme de tableau d'octets.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [AsymmetricSignatureFormatter](../)
* Classe [HashAlgorithm](../../hashalgorithm/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)