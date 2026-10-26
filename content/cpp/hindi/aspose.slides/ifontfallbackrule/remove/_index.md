---
title: Remove()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सूची से विशिष्ट FallBack फ़ॉन्ट की पहली उपस्थिति को हटाता है।
type: docs
weight: 79
url: /hi/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) विधि

सूची से विशेष FallBack फ़ॉन्ट की पहली उपस्थिति को हटाता है।

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | सूची से हटाने के लिए फ़ॉन्ट का नाम। |
## टिप्पणी



```cpp
// फ़ॉन्ट्स की सूची वाली एक नियम बनाता है।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// सूची से Tahoma को हटाना
newRule->Remove(u"Tahoma");
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IFontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)