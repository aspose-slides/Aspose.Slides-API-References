---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Si el modo de envoltorio es binario, escribe en el flujo el subrango especificado de bytes del array de bytes especificado; de lo contrario, convierte el subrango especificado de bytes del array de bytes especificado al tipo char_type y luego escribe el resultado en el flujo.
type: docs
weight: 79
url: /es/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Si el modo de envoltorio es binario, escribe en el flujo el subrango especificado de bytes del array de bytes especificado; de lo contrario, convierte el subrango especificado de bytes del array de bytes especificado al tipo char_type y luego escribe el resultado en el flujo.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Escribe el subrango especificado de bytes del array de bytes especificado en el flujo.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BasicSTDIOStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)