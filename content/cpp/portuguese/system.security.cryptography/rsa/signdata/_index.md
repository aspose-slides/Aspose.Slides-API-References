---
title: SignData()
second_title: Aspose.Slides para C++ - Referência da API
description: Computa o valor de hash da matriz de dados especificada usando o algoritmo de hash e o preenchimento especificados, e assina o resultado.
type: docs
weight: 131
url: /pt/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método

Computa o valor de hash da matriz de dados especificada usando o algoritmo de hash e o preenchimento especificados, e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Matriz de dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de preenchimento. retorna [RSA](../) assinatura para os dados de entrada. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método

Computa o valor de hash da matriz de dados especificada usando o algoritmo de hash e o preenchimento especificados, e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Matriz de dados de entrada. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a usar como dados de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de preenchimento. retorna [RSA](../) assinatura para os dados de entrada. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método

Computa o valor de hash do fluxo binário especificado usando o algoritmo de hash e o preenchimento especificados, e assina o resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Fluxo binário. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de preenchimento. retorna [RSA](../) assinatura para os dados de entrada. |

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Estrutura [HashAlgorithmName](../../hashalgorithmname/)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)