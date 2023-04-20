---
title: ConvertTo()
second_title: Aspose.Slides for C++ API Reference
description: Converts object to specific type.
type: docs
weight: 53
url: /cpp/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converts object to specific type.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Type to convert to. |

### Return Value

Converted object.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converts object to specific type.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use when converting objects. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Type to convert to. |

### Return Value

Converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)