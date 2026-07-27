---
title: VerifyData()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a assinatura dos dados especificados é válida.
type: docs
weight: 157
url: /pt/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método


Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de preenchimento. retorna true se a assinatura for válida, caso contrário - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método


Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes para hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de preenchimento. retorna true se a assinatura for válida, caso contrário - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método


Verifica se a assinatura do fluxo binário especificado é válida.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de preenchimento. retorna true se a assinatura for válida, caso contrário - false. |

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)