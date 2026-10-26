---
title: SignData()
second_title: Referencia de API de Aspose.Slides para C++
description: Calcula la firma del valor de entrada especificado.
type: docs
weight: 183
url: /es/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) método


Calcula la firma del valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) para leer los datos de entrada. |

### Valor devuelto

[DSA](../../dsa/) firma para los datos especificados.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) método


Calcula la firma del valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Flujo para leer los datos a firmar. |

### Valor devuelto

[DSA](../../dsa/) firma para los datos especificados.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) método


Calcula la firma del valor de entrada especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) para leer los datos de entrada. |
| offset | **int32_t** | Índice inicial del segmento del búfer de entrada. |
| count | **int32_t** | Tamaño del segmento del búfer de entrada. |

### Valor devuelto

[DSA](../../dsa/) firma para los datos especificados.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) método


Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash indicado y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. devuelve [DSA](../../dsa/) firma para los datos de entrada. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) método


Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash indicado y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Arreglo de datos de entrada. |
| offset | **int32_t** | Desplazamiento en **data**. |
| count | **int32_t** | Número de bytes a usar como datos de entrada. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. devuelve [DSA](../../dsa/) firma para los datos de entrada. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) método


Calcula el valor hash del flujo binario especificado usando el algoritmo hash indicado y firma el resultado.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flujo binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. devuelve [DSA](../../dsa/) firma para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Clase [DSACryptoServiceProvider](../)
* Clase [Stream](../../../system.io/stream/)
* Estructura [HashAlgorithmName](../../hashalgorithmname/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)