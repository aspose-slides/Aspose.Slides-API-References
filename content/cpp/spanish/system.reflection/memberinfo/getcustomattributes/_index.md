---
title: GetCustomAttributes()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual.
type: docs
weight: 66
url: /es/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const método

Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Tipo de atributo a buscar. |
| inherit | **bool** | Indica si también se deben comprobar los atributos heredados. |

## MemberInfo::GetCustomAttributes(bool) const método

Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inherit | **bool** | Indica si también se deben comprobar los atributos heredados. |

## Ver también

* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [MemberInfo](../)
* Espacio de nombres [System::Reflection](../../)
* Biblioteca [Aspose.Slides](../../../)