---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑब्जेक्ट्स को परिवर्तित करता है।
type: docs
weight: 14
url: /hi/system.componentmodel/typeconverter/convertfrom/
---
## TypeConverter::ConvertFrom(const System::SharedPtr\<System::Object\>\&) विधि


ऑब्जेक्ट्स को परिवर्तित करता है।

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<System::Object> &value)
```


### परामितियां

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को परिवर्तित करने के लिए। |

### वापसी मान

परिवर्तित ऑब्जेक्ट।

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) विधि


ऑब्जेक्ट्स को परिवर्तित करता है।

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### परामितियां

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) रूपांतरण संदर्भ जानकारी। |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | ऑब्जेक्ट्स को परिवर्तित करते समय उपयोग करने के लिए संस्कृति। |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को परिवर्तित करने के लिए। |

### वापसी मान

परिवर्तित ऑब्जेक्ट।

## TypeConverter::ConvertFrom(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) विधि


स्ट्रिंग को ऑब्जेक्ट में परिवर्तित करता है।

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFrom(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &value)
```


### परामितियां

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) रूपांतरण संदर्भ जानकारी। |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | ऑब्जेक्ट्स को परिवर्तित करते समय उपयोग करने के लिए संस्कृति। |
| value | const [System::String](../../../system/string/)\& | परिवर्तित करने के लिए मान। |

### वापसी मान

परिवर्तित ऑब्जेक्ट।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [String](../../../system/string/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)