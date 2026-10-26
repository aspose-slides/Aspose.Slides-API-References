---
title: Convert()
second_title: Aspose.Slides pro C++ API Reference
description: Informace RTTI.
type: docs
weight: 1
url: /cs/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metoda

Informace RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt, který má být převeden. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Cíl [System::TypeInfo](../../../system/typeinfo/), do kterého má být hodnota převedena. |

### Návratová hodnota

Převedená hodnota.

## Poznámky

Převede hodnotu na zadaný [System::TypeInfo](../../../system/typeinfo/).

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metoda

Převede hodnotu na zadaný [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt, který má být převeden. |
| typeCode | [TypeCode](../../../system/typecode/) | Cíl [System::TypeCode](../../../system/typecode/), do kterého má být hodnota převedena. |

### Návratová hodnota

Převedená hodnota.

## Viz také

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Object](../../../system/object/)
* třída [TypeInfo](../../../system/typeinfo/)
* třída [IFormatterConverter](../)
* jmenný prostor [System::Runtime::Serialization](../../)
* knihovna [Aspose.Slides](../../../)