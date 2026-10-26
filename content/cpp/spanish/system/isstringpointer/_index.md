---
title: IsStringPointer
second_title: Referencia de API de Aspose.Slides para C++
description: Magia de plantillas para verificar si un tipo es un puntero a cadena de caracteres.
type: docs
weight: 1743
url: /es/system/isstringpointer/
---
## IsStringPointer struct


Magia de plantillas para verificar si un tipo es un puntero a cadena de caracteres.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | tipo comprobado. |
| CharT | Tipo de carácter contra el que comprobar. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)