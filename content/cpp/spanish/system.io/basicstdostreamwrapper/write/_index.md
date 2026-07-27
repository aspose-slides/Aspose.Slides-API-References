---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Si el modo de envoltura es binary, escribe en el flujo el subrango especificado de bytes del array de bytes especificado; de lo contrario, convierte el subrango especificado de bytes del array de bytes especificado al tipo char_type y luego escribe el resultado en el flujo.
type: docs
weight: 79
url: /es/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método

Si el modo de envoltura es binary, escribe en el flujo el subrango especificado de bytes del array de bytes especificado; de lo contrario, convierte el subrango especificado de bytes del array de bytes especificado al tipo char_type y luego escribe el resultado en el flujo.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** donde comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método

Escribe el subrango especificado de bytes del array de bytes especificado en el flujo.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista del array que contiene los bytes a escribir |
| offset | **int32_t** | Un índice basado en cero del elemento en **buffer** donde comienza el subrango a escribir |
| count | **int32_t** | El número de elementos en el subrango a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)