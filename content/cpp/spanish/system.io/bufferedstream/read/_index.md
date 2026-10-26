---
title: Read()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee la cantidad especificada de bytes del flujo subyacente y los escribe en el arreglo de bytes especificado.
type: docs
weight: 53
url: /es/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo subyacente y los escribe en el arreglo de bytes especificado.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | La cantidad de bytes a leer |

### Valor de retorno

La cantidad de bytes leídos

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Lee la cantidad especificada de bytes del flujo subyacente y los escribe en el arreglo de bytes especificado.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | El arreglo de bytes donde escribir los bytes leídos |
| offset | **int32_t** | Una posición basada en 0 en **buffer** donde comenzar a escribir |
| count | **int32_t** | La cantidad de bytes a leer |

### Valor de retorno

La cantidad de bytes leídos

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BufferedStream](../)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)