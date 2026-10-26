---
title: VerifySignature()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifier la signature DSA pour les données spécifiées.
type: docs
weight: 118
url: /fr/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) méthode

Vérifie la signature [DSA](../../dsa/) pour les données spécifiées.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signé avec **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) signature. |

### Valeur de retour

true - si **rgb_signature** correspond à la signature [DSA](../../dsa/) calculée sur **rgb_hash**, sinon - false.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [DSACryptoServiceProvider](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)