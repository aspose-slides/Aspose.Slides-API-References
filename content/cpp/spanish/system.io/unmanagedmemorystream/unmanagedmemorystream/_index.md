---
title: UnmanagedMemoryStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de UnmanagedMemoryStream.
type: docs
weight: 118
url: /es/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) constructor


Construye una nueva instancia de [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pointer | **uint8_t** * | Un puntero al búfer no administrado |
| length | **int64_t** | El tamaño del búfer no administrado en bytes |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) constructor


Construye una nueva instancia de [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pointer | **uint8_t** * | Un puntero al búfer no administrado |
| length | **int64_t** | El tamaño del búfer no administrado en bytes |
| capacity | **int64_t** | La cantidad total de memoria asignada al flujo |
| access | [FileAccess](../../fileaccess/) | Especifica si el flujo debe ser solo de lectura, solo de escritura o ambos |

## Ver también

* Enum [FileAccess](../../fileaccess/)
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)