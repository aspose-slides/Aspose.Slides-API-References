---
title: Parse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un objeto que representa un valor de constante de enumeración del tipo de enumeración especificado con el nombre especificado.
type: docs
weight: 27
url: /es/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) método

Devuelve un objeto que representa un valor de constante de enumeración del tipo de enumeración especificado con el nombre especificado.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | El objeto [TypeInfo](../../typeinfo/) que representa el tipo del valor de enumeración a devolver |
| str | const [String](../../string/)\& | El nombre de la constante de enumeración |
| ignoreCase | **bool** | Especifica si se debe ignorar mayúsculas y minúsculas al interpretar el nombre de la constante de enumeración |

### Valor devuelto

Un objeto que representa el valor de la constante de enumeración cuyo nombre se especifica en **str**.

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Object](../../object/)
* Clase [TypeInfo](../../typeinfo/)
* Clase [String](../../string/)
* Clase [EnumValuesBase](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)