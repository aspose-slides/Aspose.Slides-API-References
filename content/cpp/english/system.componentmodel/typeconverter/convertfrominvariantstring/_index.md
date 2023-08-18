---
title: ConvertFromInvariantString()
second_title: Aspose.Slides for C++ API Reference
description: Converts invariant string to object.
type: docs
weight: 27
url: /system.componentmodel/typeconverter/convertfrominvariantstring/
---
## TypeConverter::ConvertFromInvariantString(const System::String\&) method


Converts invariant string to object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::String &text)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Value to convert. |

### Return Value

converted object.

## TypeConverter::ConvertFromInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) method


Converts invariant string to object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversion context information. |
| text | const [System::String](../../../system/string/)\& | Value to convert. |

### Return Value

converted object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)