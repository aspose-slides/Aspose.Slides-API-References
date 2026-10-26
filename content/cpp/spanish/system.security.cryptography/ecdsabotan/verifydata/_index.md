---
title: VerifyData()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica que la firma de los datos especificados sea válida.
type: docs
weight: 170
url: /es/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) método

Verifica que la firma de los datos especificados sea válida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos firmados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos de la firma. devuelve true si la firma es válida, de lo contrario - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) método

Verifica que la firma de los datos especificados sea válida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos firmados. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes para hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos de la firma. devuelve true si la firma es válida, de lo contrario - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) método

Verifica que la firma del flujo binario especificado sea válida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Datos firmados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos de la firma. devuelve true si la firma es válida, de lo contrario - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica que la firma de los datos especificados sea válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos firmados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos de la firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. devuelve true si la firma es válida, de lo contrario - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica que la firma de los datos especificados sea válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos firmados. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes para hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos de la firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. devuelve true si la firma es válida, de lo contrario - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) método

Verifica que la firma del flujo binario especificado sea válida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Datos firmados. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos de la firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo de hash. devuelve true si la firma es válida, de lo contrario - false. |

## Véase también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Clase [ECDsaBotan](../)
* Estructura [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)