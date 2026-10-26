---
title: ConvertTo()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: ऑब्जेक्ट को विशिष्ट प्रकार में बदलता है।
type: docs
weight: 14
url: /hi/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) मेथड

ऑब्जेक्ट को विशिष्ट प्रकार में बदलता है।

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) परिवर्तन संदर्भ जानकारी। |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | ऑब्जेक्ट्स को बदलते समय उपयोग करने के लिये संस्कृति। |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | बदलने हेतु एक ऑब्जेक्ट। |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | जिस प्रकार में बदलना है। |

### रिटर्न वैल्यू

परिवर्तित ऑब्जेक्ट।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* क्लास [CultureInfo](../../../system.globalization/cultureinfo/)
* क्लास [TypeInfo](../../../system/typeinfo/)
* क्लास [FontConverter](../)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)