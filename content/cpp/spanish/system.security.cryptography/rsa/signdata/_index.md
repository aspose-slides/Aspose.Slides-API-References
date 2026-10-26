---
title: SignData()
second_title: Referencia de la API de Aspose.Slides para C++
description: Calcula el valor hash del arreglo de datos especificado utilizando el algoritmo hash y el padding especificados, y firma el resultado.
type: docs
weight: 131
url: /es/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método


Calcula el valor hash del arreglo de datos especificado utilizando el algoritmo hash y el padding especificados, y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de padding. Devuelve la firma [RSA](../) para los datos de entrada. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método


Calcula el valor hash del arreglo de datos especificado utilizando el algoritmo hash y el padding especificados, y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes a usar como datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de padding. Devuelve la firma [RSA](../) para los datos de entrada. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) método


Calcula el valor hash del flujo binario especificado utilizando el algoritmo hash y el padding especificados, y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flujo binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modo de padding. Devuelve la firma [RSA](../) para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Clase [RSASignaturePadding](../../rsasignaturepadding/)
* Clase [RSA](../)
* Estructura [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)