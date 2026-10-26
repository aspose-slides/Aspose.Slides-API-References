---
title: Delimit()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: सेपरेटर अक्षर (कोष्ठकों के बिना) के साथ चाइल्ड तत्वों को सीमित करता है
type: docs
weight: 209
url: /hi/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) विधि

सेपरेटर अक्षर (कोष्ठकों के बिना) के साथ चाइल्ड तत्वों को सीमित करता है

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char16_t | सेपरेटर अक्षर |

### रिटर्न मान

[IMathDelimiter](../../imathdelimiter/) प्रकार का गणित तत्व

## टिप्पणी

उदाहरण:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)