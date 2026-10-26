---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Si el modo de envoltura es binario, lee el número especificado de bytes del flujo, de lo contrario lee el número especificado de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en el array de bytes especificado. ¡No soportado!
type: docs
weight: 66
url: /es/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Si el modo de envoltura es binario, lee el número especificado de bytes del flujo; de lo contrario, lee el número especificado de caracteres y los convierte al tipo **uint8_t**. Escribe el resultado de la lectura en el array de bytes especificado. ¡No soportado!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en cero en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

Número de bytes o caracteres leídos

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lee el número especificado de bytes del flujo y los escribe en el array de bytes especificado.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en cero en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor de retorno

El número de bytes leídos

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BasicSTDOStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)