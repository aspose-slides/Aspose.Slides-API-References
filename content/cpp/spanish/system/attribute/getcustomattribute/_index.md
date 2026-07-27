---
title: GetCustomAttribute()
second_title: Aspose.Slides para C++ Referencia de API
description: Devuelve un atributo personalizado de un tipo especificado aplicado al tipo especificado.
type: docs
weight: 1
url: /es/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) método

Devuelve un atributo personalizado del tipo especificado aplicado al tipo especificado.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Tipo de atributo del cual se recupera |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Tipo del atributo a recuperar |

### Valor devuelto

Un atributo recuperado o null si el tipo especificado no tiene un atributo del tipo especificado.

## Ver también

* Typedef [ptr](../../object/ptr/)
* Clase [TypeInfo](../../typeinfo/)
* Clase [Attribute](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)