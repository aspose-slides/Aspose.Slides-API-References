---
title: Write()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe el subrango especificado de bytes del arreglo de bytes especificado en el flujo subyacente.
type: docs
weight: 66
url: /es/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado en el flujo subyacente.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del ellemnet en **buffer** en el cual comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado en el flujo subyacente.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en 0 del ellemnet en **buffer** en el cual comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BufferedStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)