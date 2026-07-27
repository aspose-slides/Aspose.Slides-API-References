---
title: GetName()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nombre de la constante de enumeración que tiene el valor especificado.
type: docs
weight: 40
url: /es/system/enum/getname/
---
## Enum::GetName(T) método


Devuelve el nombre de la constante de enumeración que tiene el valor especificado.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El valor de la constante de enumeración cuyo nombre se va a devolver |

### Valor devuelto

El nombre de la constante de enumeración especificada

## Ver también

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)