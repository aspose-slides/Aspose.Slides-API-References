---
title: HashData()
second_title: Référence de l'API Aspose.Slides for C++
description: Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage spécifié.
type: docs
weight: 105
url: /fr/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage spécifié.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) à hacher. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à hacher. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorithme de hachage. |

### Valeur de retour

Données hachées.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) méthode


Calcule la valeur de hachage du flux binaire spécifié en utilisant l'algorithme de hachage spécifié.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Flux binaire à hacher. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorithme de hachage. |

### Valeur de retour

Données hachées.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [ECDsaBotan](../)
* Structure [HashAlgorithmName](../../hashalgorithmname/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)