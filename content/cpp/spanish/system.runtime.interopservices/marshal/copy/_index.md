---
title: Copy()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementa la semántica de public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /es/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) método


Implementa public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semántica.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| container | Tipo de contenedor de destino. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const IntPtr | Puntero a los datos de origen. |
| destination | container\&& | Contenedor donde copiar los datos. |
| startIndex | int | Índice de inicio de origen. |
| length | int | Número de elementos a copiar. |

## Marshal::Copy(const void *, container\&&, int, int) método


Implementa public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semántica.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| container | Tipo de contenedor de destino. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const void * | Puntero a los datos de origen. |
| destination | container\&& | Contenedor donde copiar los datos. |
| startIndex | int | Índice de inicio de origen. |
| length | int | Número de elementos a copiar. |

## Marshal::Copy(const container\&, int, void *, int) método


Implementa public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| container | Tipo de contenedor de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const container\& | Puntero a los datos de origen. |
| startIndex | int | Índice de inicio de origen. |
| destination | void * | Puntero a los datos de destino. |
| length | int | Número de elementos a copiar. |

## Marshal::Copy(const container\&, int, IntPtr, int) método


Implementa public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| container | Tipo de contenedor de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const container\& | Puntero a los datos de origen. |
| startIndex | int | Índice de inicio de origen. |
| destination | IntPtr | Puntero a los datos de destino. |
| length | int | Número de elementos a copiar. |

## Ver también

* Clase [Marshal](../)
* Espacio de nombres [System::Runtime::InteropServices](../../)
* Biblioteca [Aspose.Slides](../../../)