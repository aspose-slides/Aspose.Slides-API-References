---
title: Write()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe el subrango especificado de bytes del array de bytes especificado al flujo.
type: docs
weight: 209
url: /es/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Escribe el subrango especificado de bytes del array de bytes especificado al flujo.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array que contiene los bytes a escribir. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de elementos en el subrango a escribir. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Escribe el subrango especificado de bytes del array de bytes especificado al flujo.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** donde comienza el subrango a escribir |
| size | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [NetworkStream](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)