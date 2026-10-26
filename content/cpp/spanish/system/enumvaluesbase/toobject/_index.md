---
title: ToObject()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor entero sin signo de 64 bits especificado a un miembro de enumeración.
type: docs
weight: 40
url: /es/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) método

Convierte el valor entero sin signo de 64 bits especificado a un miembro de enumeración.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | El tipo de enumeración a devolver. |
| value | **uint64_t** | El valor a convertir en un miembro de enumeración. |

### Valor devuelto

Una instancia de la enumeración establecida al valor.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) método

Convierte el objeto especificado con un valor entero a un miembro de enumeración.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | El tipo de enumeración a devolver. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El valor a convertir en un miembro de enumeración. |

### Valor devuelto

Un objeto de enumeración cuyo valor es el valor.

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Object](../../object/)
* Clase [TypeInfo](../../typeinfo/)
* Clase [EnumValuesBase](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)