---
title: EnumValuesBase
second_title: Referencia de API de Aspose.Slides para C++
description: Una clase base para una clase que representa la información de metadatos del tipo enumeración.
type: docs
weight: 807
url: /es/system/enumvaluesbase/
---
## EnumValuesBase clase


Una clase base para una clase que representa la información de metadatos del tipo enumeración.

```cpp
class EnumValuesBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Recupera una matriz de los nombres de las constantes en una enumeración especificada. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Devuelve el tipo subyacente de la enumeración especificada. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Devuelve una matriz que contiene todos los valores del tipo de enumeración especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Devuelve un objeto que representa un valor de la constante de enumeración del tipo de enumeración especificado con el nombre especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Convierte el valor entero sin signo de 64 bits especificado a un miembro de enumeración. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Convierte el objeto especificado con un valor entero a un miembro de enumeración. |
## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)