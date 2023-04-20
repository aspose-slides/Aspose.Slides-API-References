---
title: Convert()
second_title: Aspose.Slides for C++ API Reference
description: RTTI information.
type: docs
weight: 1
url: /cpp/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


RTTI information.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to be converted. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | The [System::TypeInfo](../../../system/typeinfo/) into which value is to be converted. |

### Return Value

The converted value.
## Remarks


Converts a value to the given [System::TypeInfo](../../../system/typeinfo/). 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Converts a value to the given [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The object to be converted. |
| typeCode | [TypeCode](../../../system/typecode/) | The [System::TypeCode](../../../system/typecode/) into which value is to be converted. |

### Return Value

The converted value.

## See Also

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)