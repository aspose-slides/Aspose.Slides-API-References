---
title: SignData()
second_title: Referência da API Aspose.Slides para C++
description: Calcula o valor hash do array de dados especificado e assina o resultado.
type: docs
weight: 131
url: /pt/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) método


Calcula o valor hash do array de dados especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array de dados de entrada. retorna assinatura ECDSA para os dados de entrada. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) método


Calcula o valor hash do array de dados especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array de dados de entrada. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a usar como dados de entrada. retorna assinatura ECDSA para os dados de entrada. |

## ECDsaBotan::SignData(const StreamPtr\&) método


Calcula o valor hash do fluxo binário especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Fluxo binário. retorna assinatura ECDSA para os dados de entrada. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) método


Calcula o valor hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array de dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna assinatura ECDSA para os dados de entrada. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) método


Calcula o valor hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array de dados de entrada. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a usar como dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna assinatura ECDSA para os dados de entrada. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) método


Calcula o valor hash do fluxo binário especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Fluxo binário. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna assinatura ECDSA para os dados de entrada. |

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)