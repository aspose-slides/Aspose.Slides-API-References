---
title: VerifySignature()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifier la signature DSA pour les données spécifiées.
type: docs
weight: 14
url: /fr/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) méthode


Vérifier la signature [DSA](../) pour les données spécifiées.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signé avec **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) signature. |

### Valeur de retour

true - si **rgb_signature** correspond à la [DSA](../) signature calculée sur **rgb_hash**, sinon - false.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [DSA](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)