---
title: CreateMathBar()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: तत्व पर लागू करके एक गणितिक बार बनाएं
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) विधि

तत्व पर लागू करके एक गणितिक बार बनाएं

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply bar |

### रिटर्न वैल्यू

नया गणितिक बार तत्व

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) विधि

तत्व पर लागू करके एक गणितिक बार बनाएं

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Math element to apply bar |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of the bar |

### रिटर्न वैल्यू

नया गणितिक बार तत्व

## संबंधित देखें

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBar](../../imathbar/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBarFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)