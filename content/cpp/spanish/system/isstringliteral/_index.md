---
title: IsStringLiteral
second_title: Referencia de API de Aspose.Slides para C++
description: Magia de plantillas para comprobar si un tipo es un literal de cadena.
type: docs
weight: 1730
url: /es/system/isstringliteral/
---
## IsStringLiteral estructura


Magia de plantillas para comprobar si un tipo es un literal de cadena.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```



### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | tipo verificado. |
| CharT | tipo de carácter contra el cual comprobar. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)