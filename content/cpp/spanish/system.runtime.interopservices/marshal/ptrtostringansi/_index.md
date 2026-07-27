---
title: PtrToStringAnsi()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una cadena String administrada a partir de una cadena UTF8 sin administrar terminada en cero.
type: docs
weight: 274
url: /es/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) método


Crea un [String](../../../system/string/) administrado a partir de una cadena UTF8 terminada en cero no administrada.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | IntPtr | Puntero a la cadena no administrada. |

### Valor devuelto

Una cadena administrada.

## Marshal::PtrToStringAnsi(IntPtr, int) método


Crea un [String](../../../system/string/) administrado a partir de una cadena UTF8 no administrada.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | IntPtr | Puntero a la cadena no administrada. |
| length | int | Longitud de la cadena no administrada. |

### Valor devuelto

Una cadena administrada.

## Ver también

* Clase [String](../../../system/string/)
* Clase [Marshal](../)
* Espacio de nombres [System::Runtime::InteropServices](../../)
* Biblioteca [Aspose.Slides](../../../)