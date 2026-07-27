---
title: EnumValues
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona información meta sobre los constantes de enumeración del tipo **E**.
type: docs
weight: 794
url: /es/system/enumvalues/
---
## EnumValues clase


Proporciona información meta sobre los constantes de enumeración del tipo **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| E | El tipo de enumeración |
## Métodos

| Método | Descripción |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Construye una instancia. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Devuelve un array que contiene todos los nombres de la enumeración **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Recupera un array de los nombres de los constantes en una enumeración especificada. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Devuelve el tipo subyacente de la enumeración especificada. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Devuelve el tipo subyacente de la enumeración especificada. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Devuelve el valor empaquetado del constante de enumeración con el nombre especificado. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Devuelve el valor empaquetado del constante de enumeración con el valor especificado. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Devuelve un array que contiene todos los valores de la enumeración **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Devuelve un array que contiene todos los valores del tipo de enumeración especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Devuelve un objeto que representa un valor de constante de enumeración del tipo de enumeración especificado con el nombre especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Convierte el valor entero sin signo de 64 bits especificado a un miembro de enumeración. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Convierte el objeto especificado con un valor entero a un miembro de enumeración. |
| virtual  [~EnumValues](./~enumvalues/)() | Destructor. |

## Ver también

* Clase [EnumValuesBase](../enumvaluesbase/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)