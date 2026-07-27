---
title: IsStringByteSequence
second_title: Referencia de API de Aspose.Slides para C++
description: Magia de plantillas para comprobar si un tipo es una secuencia de caracteres de cadena.
type: docs
weight: 1717
url: /es/system/isstringbytesequence/
---
## IsStringByteSequence struct

Magia de plantillas para comprobar si un tipo es una secuencia de caracteres de cadena.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | tipo comprobado. |
| CharT | Tipo de carácter contra el que se verifica. |

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)