---
title: Read()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee la cantidad especificada de bytes del flujo y los escribe en el array de bytes especificado.
type: docs
weight: 391
url: /es/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lee la cantidad especificada de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor devuelto

El número de bytes leídos

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lee la cantidad especificada de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | El array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor devuelto

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [SslStream](../)
* Espacio de nombres [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)