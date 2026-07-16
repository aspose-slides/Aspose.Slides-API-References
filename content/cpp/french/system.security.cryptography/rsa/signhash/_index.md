---
title: SignHash()
second_title: Référence API Aspose.Slides pour C++
description: Calcule la signature pour la valeur de hachage spécifiée.
type: docs
weight: 144
url: /fr/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) méthode

Calcule la signature pour la valeur de hachage spécifiée.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valeur de hachage. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorithme de hachage. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Mode de remplissage. renvoie [RSA](../) signature pour le hachage spécifié. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Espace de noms [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)