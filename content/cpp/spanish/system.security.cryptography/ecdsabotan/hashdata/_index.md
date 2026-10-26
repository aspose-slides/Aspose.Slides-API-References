---
title: HashData()
second_title: Referencia de API de Aspose.Slides para C++
description: Calcula el valor de hash del arreglo de datos especificado usando el algoritmo de hash especificado.
type: docs
weight: 105
url: /es/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) método

Calcula el valor de hash del arreglo de datos especificado usando el algoritmo de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) para hashear. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes a hashear. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |

### Valor de retorno

Datos con hash.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) método

Calcula el valor de hash del flujo binario especificado usando el algoritmo de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Flujo binario a hashear. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo de hash. |

### Valor de retorno

Datos con hash.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)