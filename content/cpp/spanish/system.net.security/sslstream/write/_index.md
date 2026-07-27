---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe el array de bytes especificado en el flujo.
type: docs
weight: 404
url: /es/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) método


Escribe el array de bytes especificado en el flujo.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array de bytes a escribir. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Escribe el subrango de bytes especificado del array de bytes especificado en el flujo.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) método


Escribe el array de bytes especificado en el flujo.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | El array de bytes a escribir. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Escribe el subrango de bytes especificado del array de bytes especificado en el flujo.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | El array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [SslStream](../)
* Espacio de nombres [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)