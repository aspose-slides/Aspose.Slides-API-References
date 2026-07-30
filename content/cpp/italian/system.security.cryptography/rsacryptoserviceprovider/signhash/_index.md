---
title: SignHash()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola la firma per il valore hash specificato.
type: docs
weight: 196
url: /it/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metodo


Calcola la firma per il valore hash specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valore hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modalità di padding. restituisce [RSA](../../rsa/) firma per l'hash specificato. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metodo


Calcola la firma del valore di input specificato. Non implementato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valore hash dei dati da firmare. |
| str | const [String](../../../system/string/)\& | Identificatore dell'algoritmo hash usato per creare l'hash. |

### Valore di ritorno

[RSA](../../rsa/) firma per i dati specificati.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSACryptoServiceProvider](../)
* Classe [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)