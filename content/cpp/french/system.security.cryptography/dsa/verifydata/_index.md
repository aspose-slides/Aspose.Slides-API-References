---
title: VerifyData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie que la signature des données spécifiées est valide.
type: docs
weight: 92
url: /fr/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) méthode

Vérifie que la signature des données spécifiées est valide.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données signées. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données de signature. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie true si la signature est valide, sinon false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) méthode

Vérifie que la signature des données spécifiées est valide.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données signées. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à hacher. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données de signature. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie true si la signature est valide, sinon false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) méthode

Vérifie que la signature du flux binaire spécifié est valide.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Données signées. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données de signature. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie true si la signature est valide, sinon false. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [DSA](../)
* Structure [HashAlgorithmName](../../hashalgorithmname/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)