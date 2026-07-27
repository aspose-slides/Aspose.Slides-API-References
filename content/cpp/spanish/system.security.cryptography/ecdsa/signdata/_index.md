---
title: SignData()
second_title: Referencia de la API de Aspose.Slides para C++
description: Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado y firma el resultado.
type: docs
weight: 79
url: /es/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) método

Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. devuelve la firma ECDSA para los datos de entrada. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) método

Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes a usar como datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. devuelve la firma ECDSA para los datos de entrada. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) método

Calcula el valor hash del flujo binario especificado usando el algoritmo hash especificado y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flujo binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. devuelve la firma ECDSA para los datos de entrada. |

## Ver también

* Definición de tipo [ByteArrayPtr](../../../system/bytearrayptr/)
* Definición de tipo [StreamPtr](../../../system/streamptr/)
* Clase [ECDsa](../)
* Estructura [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)