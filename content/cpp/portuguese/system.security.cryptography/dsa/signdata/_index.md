---
title: SignData()
second_title: Referência da API Aspose.Slides para C++
description: Calcula o valor hash da matriz de dados especificada usando o algoritmo de hash especificado e assina o resultado.
type: docs
weight: 79
url: /pt/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) método

Calcula o valor hash da matriz de dados especificada usando o algoritmo de hash especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Matriz de dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna a assinatura [DSA](../) para os dados de entrada. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) método

Calcula o valor hash da matriz de dados especificada usando o algoritmo de hash especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Matriz de dados de entrada. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a usar como dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna a assinatura [DSA](../) para os dados de entrada. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) método

Calcula o valor hash do fluxo binário especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Fluxo binário. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna a assinatura [DSA](../) para os dados de entrada. |

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)