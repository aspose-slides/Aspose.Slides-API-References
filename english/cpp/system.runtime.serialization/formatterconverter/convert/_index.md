---
title: Convert()
second_title: Aspose.Slides for C++ API Reference
description: "Converts a value to the given System::TypeInfo."
type: docs
weight: 1
url: /cpp/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert([System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>, const [TypeInfo](../../../system/typeinfo/)\&) method


Converts a value to the given [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to be converted. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | The [System::TypeInfo](../../../system/typeinfo/) into which value is to be converted. |

### Return Value

The converted value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
## FormatterConverter::Convert([System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>, [TypeCode](../../../system/typecode/)) method


Converts a value to the given [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to be converted. |
| typeCode | [TypeCode](../../../system/typecode/) | The [System::TypeCode](../../../system/typecode/) into which value is to be converted. |

### Return Value

The converted value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [TypeCode](../../../system/typecode/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
