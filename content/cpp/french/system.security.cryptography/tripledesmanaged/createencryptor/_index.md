---
title: CreateEncryptor()
second_title: Référence API Aspose.Slides pour C++
description: Crée un objet encryptor avec des paramètres explicites.
type: docs
weight: 1
url: /fr/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) méthode


Crée un objet encryptor avec des paramètres explicites.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Clé de chiffrement sous forme de tableau d'octets. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valeur initiale sous forme de tableau d'octets. |

### Valeur de retour

Objet encryptor nouvellement créé.

## TripleDESManaged::CreateEncryptor() méthode


Crée un objet encryptor avec les paramètres définis par l'objet d'algorithme.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) méthode


Crée un objet encryptor avec les paramètres définis par l'objet d'algorithme.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../../icryptotransform/)
* Classe [TripleDESManaged](../)
* Espace de noms [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)