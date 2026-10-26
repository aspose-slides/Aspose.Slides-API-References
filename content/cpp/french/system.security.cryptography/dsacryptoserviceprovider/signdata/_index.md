---
title: SignData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule la signature de la valeur d'entrée spécifiée.
type: docs
weight: 183
url: /fr/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) méthode


Calcule la signature de la valeur d’entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) pour lire les données d’entrée. |

### Valeur de retour

[DSA](../../dsa/) signature pour les données spécifiées.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) méthode


Calcule la signature de la valeur d’entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Flux pour lire les données à signer. |

### Valeur de retour

[DSA](../../dsa/) signature pour les données spécifiées.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) méthode


Calcule la signature de la valeur d’entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) pour lire les données d’entrée. |
| offset | **int32_t** | Index de début de la tranche du tampon d’entrée. |
| count | **int32_t** | Taille de la tranche du tampon d’entrée. |

### Valeur de retour

[DSA](../../dsa/) signature pour les données spécifiées.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l’algorithme de hachage indiqué, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d’entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie [DSA](../../dsa/) signature pour les données d’entrée. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) méthode


Calcule la valeur de hachage du tableau de données spécifié en utilisant l’algorithme de hachage indiqué, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tableau de données d’entrée. |
| offset | **int32_t** | Décalage dans **data**. |
| count | **int32_t** | Nombre d’octets à utiliser comme données d’entrée. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie [DSA](../../dsa/) signature pour les données d’entrée. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) méthode


Calcule la valeur de hachage du flux binaire spécifié en utilisant l’algorithme de hachage indiqué, puis signe le résultat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flux binaire. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorithme de hachage. renvoie [DSA](../../dsa/) signature pour les données d’entrée. |

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)