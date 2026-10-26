---
title: CreateMathBar()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एलेमेंट पर लागू करके एक गणित बार बनाएं
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) विधि

एलेमेंट पर लागू करके एक math bar बनाएं

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बार लागू करने हेतु math element |

### रिटर्न वैल्यू

नया math bar तत्व

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) विधि

एलेमेंट पर लागू करके एक math bar बनाएं

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बार लागू करने हेतु Math element |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | बार की स्थिति |

### रिटर्न वैल्यू

नया math bar तत्व

## संदर्भ

* एन्यूम [MathTopBotPositions](../../mathtopbotpositions/)
* टाइपडैफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBar](../../imathbar/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBarFactory](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)