---
title: Convert()
second_title: Referencia de API de Aspose.Slides para C++
description: Información RTTI.
type: docs
weight: 1
url: /es/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) método


Información RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El objeto a convertir. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | El [System::TypeInfo](../../../system/typeinfo/) al que se convertirá el valor. |

### Valor devuelto

El valor convertido.
## Observaciones


Convierte un valor al [System::TypeInfo](../../../system/typeinfo/) especificado. 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) método


Convierte un valor al [System::TypeCode](../../../system/typecode/) especificado.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El objeto a convertir. |
| typeCode | [TypeCode](../../../system/typecode/) | El [System::TypeCode](../../../system/typecode/) al que se convertirá el valor. |

### Valor devuelto

El valor convertido.

## Ver también

* Enumeración [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [IFormatterConverter](../)
* Espacio de nombres [System::Runtime::Serialization](../../)
* Biblioteca [Aspose.Slides](../../../)