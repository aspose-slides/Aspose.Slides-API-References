---
title: VerifyHash()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie la signature des données.
type: docs
weight: 118
url: /fr/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) method


Vérifie la signature des données.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hachage calculé pour les données reçues. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signature telle que reçue. |

### Valeur de retour

True si la signature est valide, false sinon.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [ECDsa](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)