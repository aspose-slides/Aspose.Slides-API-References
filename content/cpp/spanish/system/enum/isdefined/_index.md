---
title: IsDefined()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el valor especificado es un miembro del tipo de enumeración E.
type: docs
weight: 27
url: /es/system/enum/isdefined/
---
## Enum::IsDefined(E) método

Determina si el valor especificado es un miembro del tipo de enumeración **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | E | El valor a comprobar |

### Valor de retorno

True si **value** es un miembro de la enumeración **E**, de lo contrario - false

## Enum::IsDefined(T) método

Determina si el valor especificado es un miembro del tipo de enumeración **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T | El valor a comprobar |

### Valor de retorno

True si **value** es un miembro de la enumeración **T**, de lo contrario - false

## Enum::IsDefined(const String\&) método

Determina si el valor con el nombre especificado está entre los miembros del enum **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../string/)\& | El nombre a comprobar |

### Valor de retorno

True si existe un miembro del enum **E** con el nombre especificado.

## Ver también

* Typedef [UnderlyingType](../underlyingtype/)
* Clase [String](../../string/)
* Estructura [Enum](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)