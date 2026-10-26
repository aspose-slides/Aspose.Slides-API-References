---
title: Convert()
second_title: Aspose.Slides C++ API referencia
description: "Átalakít egy értéket a megadott System::TypeInfo típusba."
type: docs
weight: 1
url: /hu/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Átalakít egy értéket a megadott [System::TypeInfo](../../../system/typeinfo/)-ba.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Az átalakítandó objektum. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | A [System::TypeInfo](../../../system/typeinfo/), amelybe az értéket átalakítják. |

### Return Value

Az átalakított érték.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Átalakít egy értéket a megadott [System::TypeCode](../../../system/typecode/)-ba.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Az átalakítandó objektum. |
| typeCode | [TypeCode](../../../system/typecode/) | A [System::TypeCode](../../../system/typecode/), amelybe az értéket átalakítják. |

### Return Value

Az átalakított érték.

## See Also

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [FormatterConverter](../)
* Névtér [System::Runtime::Serialization](../../)
* Könyvtár [Aspose.Slides](../../../)