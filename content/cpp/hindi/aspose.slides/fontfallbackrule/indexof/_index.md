---
title: IndexOf()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह में निर्दिष्ट नियम का अनुक्रमांक लौटाता है।
type: docs
weight: 157
url: /hi/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) विधि

संग्रह में निर्दिष्ट नियम का अनुक्रमांक लौटाता है।

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | खोजने के लिए फ़ॉन्ट का नाम। |

### वापसी मान

फ़ॉन्ट का अनुक्रमांक या -1 यदि फ़ॉन्ट सूची में नहीं मिला।

## टिप्पणियाँ



```cpp
// फ़ॉन्ट्स की सूची युक्त एक नियम बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma का अनुक्रमांक प्राप्त करें।
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [FontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)