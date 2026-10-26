---
title: Delimit()
second_title: Aspose.Slides for C++ API संदर्भ
description: सेपरेटर अक्षर के साथ सभी चाइल्ड एलिमेंट्स को डिलिमिट करता है (ब्रैकेट्स के बिना)
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) मेथड


सेपरेटर अक्षर के साथ सभी चाइल्ड एलिमेंट्स को डिलिमिट करता है (ब्रैकेट्स के बिना)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| separatorCharacter | char16_t | सेपरेटर के रूप में प्रयुक्त वर्ण |

### वापसी मान

[IMathDelimiter](../../imathdelimiter/) तत्व का उदाहरण
## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## संबंधित देखें

* टाइपडॅफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathDelimiter](../../imathdelimiter/)
* क्लास [IMathBlock](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)