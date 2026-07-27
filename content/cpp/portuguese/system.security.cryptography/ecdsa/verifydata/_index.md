---
title: VerifyData()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a assinatura dos dados especificados é válida.
type: docs
weight: 105
url: /pt/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados de assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes para hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados de assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica se a assinatura do fluxo binário especificado é válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados de assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna true se a assinatura for válida, caso contrário - false. |

## Veja também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)