---
title: Delimit()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमित करता है
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) विधि

निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमित करता है

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char16_t | डिलिमिटर अक्षर |

### रिटर्न वैल्यू

डिलिमिटर अक्षर लागू करने के बाद यह ऑब्जेक्ट
## टिप्पणी



उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)