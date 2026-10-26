---
title: Convert()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Informacje RTTI.
type: docs
weight: 1
url: /pl/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metoda


Informacje RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Obiekt do konwersji. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | [System::TypeInfo](../../../system/typeinfo/) do którego ma zostać skonwertowana wartość. |

### Wartość zwracana

Skonwertowana wartość.
## Uwagi


Konwertuje wartość do podanego [System::TypeInfo](../../../system/typeinfo/). 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metoda


Konwertuje wartość do podanego [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Obiekt do konwersji. |
| typeCode | [TypeCode](../../../system/typecode/) | [System::TypeCode](../../../system/typecode/) do którego ma zostać skonwertowana wartość. |

### Wartość zwracana

Skonwertowana wartość.

## Zobacz także

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)