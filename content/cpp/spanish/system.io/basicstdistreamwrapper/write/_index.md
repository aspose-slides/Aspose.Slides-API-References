---
title: Write()
second_title: Referencia de la API de Aspose.Slides para C++
description: Si el modo de encapsulado es binario, escribe en el flujo el subrango especificado de bytes del arreglo de bytes especificado, de lo contrario convierte el subrango especificado de bytes del arreglo de bytes especificado al tipo char_type y luego escribe el resultado en el flujo. ¡No compatible!
type: docs
weight: 79
url: /es/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream. ¡No compatible!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir. |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | **int32_t** | El número de elementos en el subrango a escribir. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del arreglo que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BasicSTDIStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)