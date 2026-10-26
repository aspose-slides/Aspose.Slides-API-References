---
title: VerifyData()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a assinatura dos dados especificados é válida.
type: docs
weight: 170
url: /pt/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) método

Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) método

Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) método

Verifica se a assinatura do fluxo binário especificado é válida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica se a assinatura dos dados especificados é válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados assinados. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna true se a assinatura for válida, caso contrário - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica se a assinatura do fluxo binário especificado é válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dados assinados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados da assinatura. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna true se a assinatura for válida, caso contrário - false. |

## Ver também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)