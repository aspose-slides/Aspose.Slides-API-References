---
title: Convert()
second_title: Aspose.Slides C++ API referenciája
description: RTTI információ.
type: docs
weight: 1
url: /hu/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


RTTI információ.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Az átalakítandó objektum. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | A [System::TypeInfo](../../../system/typeinfo/), amelybe az érték átalakítandó. |

### Visszatérési érték

Az átalakított érték.
## Megjegyzések


Átalakít egy értéket a megadott [System::TypeInfo](../../../system/typeinfo/)-ra. 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Átalakít egy értéket a megadott [System::TypeCode](../../../system/typecode/)-ra.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Az átalakítandó objektum. |
| typeCode | [TypeCode](../../../system/typecode/) | A [System::TypeCode](../../../system/typecode/), amelybe az érték átalakítandó. |

### Visszatérési érték

Az átalakított érték.

## Lásd még

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)