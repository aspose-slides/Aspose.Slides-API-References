---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.
type: docs
weight: 196
url: /es/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | La matriz de bytes donde se escribirán los bytes leídos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes a leer. |

### Valor devuelto

El número de bytes leídos.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista de la matriz de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| size | **int32_t** | El número de bytes a leer |

### Valor devuelto

El número de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [NetworkStream](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)