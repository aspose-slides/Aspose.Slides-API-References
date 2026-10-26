---
title: SignData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule la signature de la valeur d'entrée spécifiée.
type: docs
weight: 183
url: /fr/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) méthode

Calcule la signature de la valeur d'entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) pour lire les données d'entrée depuis. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorithme de hachage à utiliser. |

### Valeur de retour

[RSA](../../rsa/) signature pour les données spécifiées.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) méthode

Calcule la signature de la valeur d'entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Flux pour lire les données à signer depuis. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorithme de hachage à utiliser. |

### Valeur de retour

[RSA](../../rsa/) signature pour les données spécifiées.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) méthode

Calcule la signature de la valeur d'entrée spécifiée.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) pour lire les données d'entrée depuis. |
| offset | **int32_t** | Index de début de la tranche du tampon d'entrée. |
| count | **int32_t** | Taille de la tranche du tampon d'entrée. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorithme de hachage à utiliser. |

### Valeur de retour

[RSA](../../rsa/) signature pour les données spécifiées.

## Voir aussi

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [RSACryptoServiceProvider](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)