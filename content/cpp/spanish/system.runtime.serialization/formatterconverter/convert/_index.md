---
title: Convert()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Convierte un valor al System::TypeInfo especificado."
type: docs
weight: 1
url: /es/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) método

Convierte un valor al [System::TypeInfo](../../../system/typeinfo/) dado.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El objeto a convertir. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | El [System::TypeInfo](../../../system/typeinfo/) al que se convertirá el valor. |

### Valor devuelto

El valor convertido.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) método

Convierte un valor al [System::TypeCode](../../../system/typecode/) dado.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El objeto a convertir. |
| typeCode | [TypeCode](../../../system/typecode/) | El [System::TypeCode](../../../system/typecode/) al que se convertirá el valor. |

### Valor devuelto

El valor convertido.

## Véase también

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [FormatterConverter](../)
* Espacio de nombres [System::Runtime::Serialization](../../)
* Biblioteca [Aspose.Slides](../../../)