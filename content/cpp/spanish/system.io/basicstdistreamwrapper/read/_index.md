---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Si el modo de encapsulado es binario, lee la cantidad especificada de bytes del flujo; de lo contrario, lee la cantidad especificada de caracteres y los convierte al tipo uint8_t. Escribe el resultado de la lectura en la matriz de bytes especificada.
type: docs
weight: 66
url: /es/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Si el modo de envoltura es binario, lee la cantidad especificada de bytes del flujo; de lo contrario, lee la cantidad especificada de caracteres y los convierte al tipo **uint8_t**. Escribe el resultado de la lectura en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Valor de retorno

Número de bytes o caracteres leídos

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo y los escribe en la matriz de bytes especificada.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Valor de retorno

El número de bytes leídos

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BasicSTDIStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)