---
title: ConvertToString()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ऑब्जेक्ट को स्ट्रिंग में बदलता है।
type: docs
weight: 79
url: /hi/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) मेथड

ऑब्जेक्ट को स्ट्रिंग में बदलता है।

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को परिवर्तित करने के लिए। |

### वापसी मान

परिवर्तित ऑब्जेक्ट।

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) मेथड

ऑब्जेक्ट को स्ट्रिंग में बदलता है।

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) परिवर्तन संदर्भ जानकारी। |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को परिवर्तित करने के लिए। |

### वापसी मान

परिवर्तित ऑब्जेक्ट।

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) मेथड

ऑब्जेक्ट को स्ट्रिंग में बदलता है।

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) परिवर्तन संदर्भ जानकारी। |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | ऑब्जेक्ट को परिवर्तित करते समय उपयोग करने वाली संस्कृति। |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) को परिवर्तित करने के लिए। |

### वापसी मान

परिवर्तित ऑब्जेक्ट।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Object](../../../system/object/)
* क्लास [TypeConverter](../)
* क्लास [ITypeDescriptorContext](../../itypedescriptorcontext/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* नेमस्पेस [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)