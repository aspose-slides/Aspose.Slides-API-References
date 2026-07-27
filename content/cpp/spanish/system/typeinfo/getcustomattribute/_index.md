---
title: GetCustomAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el atributo personalizado aplicado que tiene el tipo especificado y que se aplica al tipo representado por el objeto actual.
type: docs
weight: 573
url: /es/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const method

Busca el atributo personalizado aplicado que tiene el tipo especificado y que se aplica al tipo representado por el objeto actual.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | La referencia constante al objeto [TypeInfo](../) que representa el tipo del atributo a buscar |

### Valor devuelto

Un puntero a un objeto que representa el atributo encontrado, o un puntero nulo si no se encontró ningún atributo que coincida con los criterios de búsqueda

## Ver también

* Clase [SmartPtr](../../smartptr/)
* Clase [TypeInfo](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)