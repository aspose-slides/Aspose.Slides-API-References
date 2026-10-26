---
title: SignData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule la valeur de hachage du tableau de données spécifié et signe le résultat.
type: docs
weight: 131
url: /fr/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) méthode

Calcule la valeur de hachage du tableau de données spécifié et signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. renvoie la signature ECDSA pour les données d'entrée. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) méthode

Calcule la valeur de hachage du tableau de données spécifié et signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à utiliser comme données d'entrée. renvoie la signature ECDSA pour les données d'entrée. |

## ECDsaBotan::SignData(const StreamPtr\&) méthode

Calcule la valeur de hachage du flux binaire spécifié et signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flux binaire. renvoie la signature ECDSA pour les données d'entrée. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) méthode

Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage indiqué et signe le résultat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie la signature ECDSA pour les données d'entrée. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) méthode

Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage indiqué et signe le résultat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à utiliser comme données d'entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie la signature ECDSA pour les données d'entrée. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) méthode

Calcule la valeur de hachage du flux binaire spécifié en utilisant l'algorithme de hachage indiqué et signe le résultat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flux binaire. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie la signature ECDSA pour les données d'entrée. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [ECDsaBotan](../)
* Structure [HashAlgorithmName](../../hashalgorithmname/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)