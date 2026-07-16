---
title: VerifyData()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie que la signature des données spécifiées est valide.
type: docs
weight: 157
url: /fr/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) méthode

Vérifie que la signature des données spécifiées est valide.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données signées. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données de signature. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Mode de remplissage. renvoie true si la signature est valide, sinon - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) méthode

Vérifie que la signature des données spécifiées est valide.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données signées. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à hacher. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données de signature. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Mode de remplissage. renvoie true si la signature est valide, sinon - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) méthode

Vérifie que la signature du flux binaire spécifié est valide.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Données signées. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données de signature. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Mode de remplissage. renvoie true si la signature est valide, sinon - false. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Structure [HashAlgorithmName](../../hashalgorithmname/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)