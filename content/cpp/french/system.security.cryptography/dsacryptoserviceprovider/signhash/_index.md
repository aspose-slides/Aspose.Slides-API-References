---
title: SignHash()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule la signature de la valeur d'entrée spécifiée.
type: docs
weight: 196
url: /fr/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) méthode

Calcule la signature de la valeur d'entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valeur de hachage des données à signer. |
| str | const [String](../../../system/string/)\& | Identifiant de l'algorithme de hachage utilisé pour créer le hachage. |

### Valeur de retour

[DSA](../../dsa/) signature pour les données spécifiées.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [DSACryptoServiceProvider](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)