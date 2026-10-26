---
title: ConvertFromString()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्ट्रिंग को ऑब्जेक्ट में परिवर्तित करता है।
type: docs
weight: 40
url: /hi/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) method

स्ट्रिंग को ऑब्जेक्ट में परिवर्तित करता है।

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | परिवर्तित करने के लिए मान। |

### रिटर्न वैल्यू

परिवर्तित ऑब्जेक्ट।

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) method

स्ट्रिंग को ऑब्जेक्ट में परिवर्तित करता है।

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) परिवर्तन संदर्भ जानकारी। |
| text | const [System::String](../../../system/string/)\& | परिवर्तित करने के लिए मान। |

### रिटर्न वैल्यू

परिवर्तित ऑब्जेक्ट।

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) method

स्ट्रिंग को ऑब्जेक्ट में परिवर्तित करता है।

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) परिवर्तन संदर्भ जानकारी। |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | ऑब्जेक्ट परिवर्तित करते समय उपयोग करने के लिए संस्कृति। |
| text | const [System::String](../../../system/string/)\& | परिवर्तित करने के लिए मान। |

### रिटर्न वैल्यू

परिवर्तित ऑब्जेक्ट।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)