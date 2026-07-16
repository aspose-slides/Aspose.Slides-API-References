---
title: SignData()
second_title: Aspose.Slides pour C++ Référence API
description: Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat.
type: docs
weight: 131
url: /fr/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Mode de remplissage. renvoie la signature [RSA](../) pour les données d'entrée. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d'entrée. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d'octets à utiliser comme données d'entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Mode de remplissage. renvoie la signature [RSA](../) pour les données d'entrée. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) méthode


Calcule la valeur de hachage du flux binaire spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flux binaire. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Mode de remplissage. renvoie la signature [RSA](../) pour les données d'entrée. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Structure [HashAlgorithmName](../../hashalgorithmname/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)