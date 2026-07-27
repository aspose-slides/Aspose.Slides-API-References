---
title: Read()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado.
type: docs
weight: 183
url: /es/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lee la cantidad especificada de bytes del flujo y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes donde escribir los bytes leídos. |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir. |
| count | **int32_t** | La cantidad de bytes a leer. |

### Valor devuelto

El número de bytes leídos.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lee la cantidad especificada de bytes del flujo y los escribe en la vista del arreglo de bytes especificada.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del arreglo de bytes donde escribir los bytes leídos. |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir. |
| count | **int32_t** | La cantidad de bytes a leer. |

### Valor devuelto

El número de bytes leídos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [FileStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)