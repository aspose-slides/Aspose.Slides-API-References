---
title: HashData()
second_title: Aspose.Slides para C++ Referência da API
description: Calcula o valor de hash do array de dados especificado usando o algoritmo de hash especificado.
type: docs
weight: 105
url: /pt/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) método

Calcula o valor de hash do array de dados especificado usando o algoritmo de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) a hash. |
| offset | **int32_t** | Deslocamento em **data**. |
| count | **int32_t** | Número de bytes a hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |

### Valor de Retorno

Dados com hash.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) método

Calcula o valor de hash do fluxo binário especificado usando o algoritmo de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Fluxo binário a hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |

### Valor de Retorno

Dados com hash.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)