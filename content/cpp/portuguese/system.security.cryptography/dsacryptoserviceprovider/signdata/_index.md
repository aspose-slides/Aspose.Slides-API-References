---
title: SignData()
second_title: Referência da API Aspose.Slides para C++
description: Computa a assinatura do valor de entrada especificado.
type: docs
weight: 183
url: /pt/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) método


Computa a assinatura do valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) para ler os dados de entrada de. |

### Valor de Retorno

[DSA](../../dsa/) assinatura para os dados especificados.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) método


Computa a assinatura do valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Fluxo para ler os dados a serem assinados. |

### Valor de Retorno

[DSA](../../dsa/) assinatura para os dados especificados.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) método


Computa a assinatura do valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) para ler os dados de entrada de. |
| offset | **int32_t** | Índice inicial da fatia do buffer de entrada. |
| count | **int32_t** | Tamanho da fatia do buffer de entrada. |

### Valor de Retorno

[DSA](../../dsa/) assinatura para os dados especificados.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) método


Computa o valor de hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array de dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna a assinatura [DSA](../../dsa/) para os dados de entrada. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) método


Computa o valor de hash do array de dados especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array de dados de entrada. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a usar como dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna a assinatura [DSA](../../dsa/) para os dados de entrada. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) método


Computa o valor de hash do fluxo binário especificado usando o algoritmo de hash especificado e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Fluxo binário. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. retorna a assinatura [DSA](../../dsa/) para os dados de entrada. |

## Ver também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)