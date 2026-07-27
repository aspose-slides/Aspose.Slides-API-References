---
title: SignHash()
second_title: Referência da API Aspose.Slides for C++
description: Calcula a assinatura para o valor de hash especificado.
type: docs
weight: 196
url: /pt/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) método


Calcula a assinatura para o valor de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valor de hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modo de preenchimento. retorna [RSA](../../rsa/) assinatura para o hash especificado. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) método


Calcula a assinatura do valor de entrada especificado. Não implementado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Valor de hash dos dados a serem assinados. |
| str | const [String](../../../system/string/)\& | Identificador do algoritmo de hash usado para criar o hash. |

### Valor de Retorno

[RSA](../../rsa/) assinatura para os dados especificados.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSACryptoServiceProvider](../)
* Classe [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)