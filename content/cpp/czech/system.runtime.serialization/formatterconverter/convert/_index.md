---
title: Convert()
second_title: Aspose.Slides pro C++ API Reference
description: "Převede hodnotu na daný System::TypeInfo."
type: docs
weight: 1
url: /cs/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metoda


Převádí hodnotu na daný [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt, který se má převést. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Cílový [System::TypeInfo](../../../system/typeinfo/), do kterého má být hodnota převedena. |

### Návratová hodnota

Převedená hodnota.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metoda


Převádí hodnotu na daný [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt, který se má převést. |
| typeCode | [TypeCode](../../../system/typecode/) | Cílový [System::TypeCode](../../../system/typecode/), do kterého má být hodnota převedena. |

### Návratová hodnota

Převedená hodnota.

## Viz také

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [FormatterConverter](../)
* Jmenný prostor [System::Runtime::Serialization](../../)
* Knihovna [Aspose.Slides](../../../)