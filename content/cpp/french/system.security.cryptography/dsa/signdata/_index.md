---
title: SignData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage indiqué, puis signe le résultat.
type: docs
weight: 79
url: /fr/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage indiqué, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie [DSA](../) signature pour les données d'entrée. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage indiqué, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à utiliser comme données d'entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie [DSA](../) signature pour les données d'entrée. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) méthode


Calcule la valeur de hachage du flux binaire spécifié en utilisant l'algorithme de hachage indiqué, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flux binaire. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie [DSA](../) signature pour les données d'entrée. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)