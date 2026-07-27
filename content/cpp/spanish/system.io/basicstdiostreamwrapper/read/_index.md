---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Si el modo de envoltura es binario, lee la cantidad especificada de bytes del flujo; de lo contrario, lee la cantidad especificada de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en la matriz de bytes especificada.
type: docs
weight: 66
url: /es/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Si el modo de envoltura es binario, lee la cantidad especificada de bytes del flujo; de lo contrario, lee la cantidad especificada de caracteres y los convierte al tipo **uint8_t**. Escribe el resultado de la lectura en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | La matriz de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor devuelto

Número de bytes o caracteres leídos

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista de la matriz de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | El número de bytes a leer |

### Valor devuelto

El número de bytes leídos

## Ver también

* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [BasicSTDIOStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)