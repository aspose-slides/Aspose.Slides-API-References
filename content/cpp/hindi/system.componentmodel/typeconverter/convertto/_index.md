---
title: ConvertTo()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑब्जेक्ट को विशिष्ट प्रकार में रूपांतरित करता है।
type: docs
weight: 53
url: /hi/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

ऑब्जेक्ट को विशिष्ट प्रकार में रूपांतरित करता है।

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को रूपांतरित करने के लिए। |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | रूपांतरण के लिए प्रकार। |

### Return Value

Converted object.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

ऑब्जेक्ट को विशिष्ट प्रकार में रूपांतरित करता है।

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) रूपांतरण संदर्भ जानकारी। |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | वस्तुओं को रूपांतरित करते समय उपयोग करने वाली संस्कृति। |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को रूपांतरित करने के लिए। |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | रूपांतरण के लिए प्रकार। |

### Return Value

Converted object.

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [TypeConverter](../)
* क्लास [ITypeDescriptorContext](../../itypedescriptorcontext/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* नेमस्पेस [System::ComponentModel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)