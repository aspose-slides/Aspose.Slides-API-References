---
title: VerifyHash()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie la signature des données.
type: docs
weight: 222
url: /fr/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) méthode


Vérifie la signature des données.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calculé pour les données reçues. |
| str | const [String](../../../system/string/)\& | Nom de l'algorithme de hachage utilisé. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature telle qu'elle a été reçue. |

### Valeur de retour

True si la signature est valide, false sinon.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [DSACryptoServiceProvider](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)