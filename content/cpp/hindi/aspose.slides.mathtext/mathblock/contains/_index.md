---
title: Contains()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्धारित करता है कि क्या संग्रह में कोई विशिष्ट मान मौजूद है।
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/mathblock/contains/
---
## MathBlock::Contains(System::SharedPtr\<IMathElement\>) विधि

संग्रह में किसी विशिष्ट मान के अस्तित्व का निर्धारण करता है।

```cpp
bool Aspose::Slides::MathText::MathBlock::Contains(System::SharedPtr<IMathElement> item) override
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | संग्रह में स्थित करने के लिये वस्तु। |

### Return Value

यदि *item* संग्रह में मिला तो true; अन्यथा false.

## टिप्पणी

उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = mathBlock->Contains(plusElement);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)