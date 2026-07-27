---
title: SignData()
second_title: Referencia de la API de Aspose.Slides para C++
description: Calcula el valor hash del arreglo de datos especificado y firma el resultado.
type: docs
weight: 131
url: /es/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) método

Calcula el valor hash del arreglo de datos especificado y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. devuelve la firma ECDSA para los datos de entrada. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) método

Calcula el valor hash del arreglo de datos especificado y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes a usar como datos de entrada. devuelve la firma ECDSA para los datos de entrada. |

## ECDsaBotan::SignData(const StreamPtr\&) método

Calcula el valor hash del flujo binario especificado y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flujo binario. devuelve la firma ECDSA para los datos de entrada. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) método

Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. devuelve la firma ECDSA para los datos de entrada. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) método

Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes a usar como datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. devuelve la firma ECDSA para los datos de entrada. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) método

Calcula el valor hash del flujo binario especificado usando el algoritmo hash especificado y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flujo binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. devuelve la firma ECDSA para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Clase [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)