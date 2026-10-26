---
title: VerifySignature()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie la signature du hachage des données.
type: docs
weight: 40
url: /fr/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) méthode

Vérifie la signature du hachage des données.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash calculé pour les données. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Signature reçue pour les données. |

### Valeur de retour

Vrai si la signature est valide, faux sinon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [RSAPKCS1SignatureDeformatter](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)