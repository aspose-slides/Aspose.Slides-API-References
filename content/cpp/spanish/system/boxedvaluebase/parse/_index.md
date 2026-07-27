---
title: Parse()
second_title: Referencia de API de Aspose.Slides para C++
description: Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado. Un parámetro indica si se debe ignorar mayúsculas y minúsculas al interpretar la cadena que especifica el nombre de la constante de enumeración.
type: docs
weight: 53
url: /es/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) método

Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado. Un parámetro indica si se debe ignorar mayúsculas y minúsculas al interpretar la cadena que especifica el nombre de la constante de enumeración.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Especifica el tipo de la enumeración |
| str | const [String](../../string/)\& | El nombre de la constante de enumeración, cuyo valor será empaquetado |
| ignoreCase | **bool** | Especifica si se debe ignorar mayúsculas y minúsculas al interpretar la cadena que representa el nombre de la constante de enumeración |

### Valor devuelto

Un puntero compartido al objeto que representa el valor empaquetado de la constante de enumeración especificada

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) método

Empaqueta el valor de la constante de enumeración de la enumeración especificada con el nombre especificado.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Especifica el tipo de la enumeración |
| str | const [String](../../string/)\& | El nombre de la constante de enumeración, cuyo valor será empaquetado |

### Valor devuelto

Un puntero compartido al objeto que representa el valor empaquetado de la constante de enumeración especificada

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Object](../../object/)
* Clase [TypeInfo](../../typeinfo/)
* Clase [String](../../string/)
* Clase [BoxedValueBase](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)