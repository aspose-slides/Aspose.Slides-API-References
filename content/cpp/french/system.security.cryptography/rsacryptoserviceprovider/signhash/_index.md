---
title: SignHash()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule la signature pour la valeur de hachage spécifiée.
type: docs
weight: 196
url: /fr/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) méthode

Calcule la signature pour la valeur de hachage spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valeur de hachage. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorithme de hachage. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Mode de remplissage. renvoie [RSA](../../rsa/) signature pour le hachage spécifié. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) méthode

Calcule la signature de la valeur d'entrée spécifiée. Non implémenté.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valeur de hachage des données à signer. |
| str | const [String](../../../system/string/)\& | Identifiant de l'algorithme de hachage utilisé pour créer le hachage. |

### Valeur de retour

[RSA](../../rsa/) signature pour les données spécifiées.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [RSASignaturePadding](../../rsasignaturepadding/)
* classe [RSACryptoServiceProvider](../)
* classe [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* espace de noms [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)