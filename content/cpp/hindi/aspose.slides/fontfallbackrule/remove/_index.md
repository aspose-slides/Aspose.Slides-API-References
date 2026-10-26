---
title: Remove()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: सूची से एक विशिष्ट FallBack फ़ॉन्ट की पहली उपस्थिति को हटाता है।
type: docs
weight: 118
url: /hi/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) विधि


सूची से एक विशिष्ट FallBack फ़ॉन्ट की पहली उपस्थिति को हटाता है।

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | सूची से हटाने के लिये फ़ॉन्ट का नाम। |
## टिप्पणी



```cpp
// फ़ॉन्ट्स की सूची वाला नियम बनाएं।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// सूची से Tahoma हटाएँ।
newRule->Remove(u"Tahoma");
```


## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [FontFallBackRule](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)