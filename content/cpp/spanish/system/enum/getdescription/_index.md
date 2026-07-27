---
title: GetDescription()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nombre de la constante de enumeración que tiene el valor especificado.
type: docs
weight: 53
url: /es/system/enum/getdescription/
---
## Enum::GetDescription(T) método

Devuelve el nombre de la constante de enumeración que tiene el valor especificado.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El valor de la constante de enumeración cuyo nombre se debe devolver |

### Valor devuelto

El nombre de la constante de enumeración especificada

## Ver también

* Typedef [UnderlyingType](../underlyingtype/)
* Clase [String](../../string/)
* Estructura [Enum](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)