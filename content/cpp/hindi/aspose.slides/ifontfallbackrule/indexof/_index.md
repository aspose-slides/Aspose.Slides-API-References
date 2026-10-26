---
title: IndexOf()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: क्लेक्शन में निर्दिष्ट नियम का सूचकांक लौटाता है।
type: docs
weight: 118
url: /hi/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) विधि

क्लेक्शन में निर्दिष्ट नियम का सूचकांक लौटाता है।

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | खोजने के लिए फ़ॉन्ट का नाम। |

### रिटर्न वैल्यू

फ़ॉन्ट का सूचकांक या -1 यदि फ़ॉन्ट सूची में नहीं मिला।

## टिप्पणियां

```cpp
// एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Tahoma का सूचकांक प्राप्त करें
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IFontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)