---
title: GetCustomAttributes()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo.
type: docs
weight: 586
url: /es/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const método

Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const método

Devuelve una matriz que contiene objetos que representan atributos específicos aplicados al tipo.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Tipo del atributo a buscar. |
| inherit | **bool** | Indica si se deben buscar también atributos heredados. |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [SmartPtr](../../smartptr/)
* Clase [TypeInfo](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)