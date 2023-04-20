---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API Reference
description: Converts objects.
type: docs
weight: 14
url: /cpp/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) method


Converts objects.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |

### Return Value

converted object.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) method


Converts objects.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use when converting objects. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) to convert. |

### Return Value

converted object.

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method


Converts string to object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversion context information. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use when converting objects. |
| value | const [System::String](../../../system/string/)\& | Value to convert. |

### Return Value

converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [String](../../../system/string/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)