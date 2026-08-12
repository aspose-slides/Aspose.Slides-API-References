---
title: CreateMathBorderBox()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एलिमेंट पर लागू करके एक गणित बॉर्डर बॉक्स बनाएं
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) विधि

एलिमेंट पर लागू करके एक गणित बॉर्डर बॉक्स बनाएँ

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बॉर्डर बॉक्स लागू करने के लिए गणितीय तत्व |

### वापसी मान

नया बॉर्डर बॉक्स एलिमेंट

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) विधि

एलिमेंट पर लागू करके एक गणित बॉर्डर बॉक्स बनाएँ

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बॉर्डर बॉक्स लागू करने के लिए गणितीय तत्व |
| hideTop | **bool** | ऊपरी किनारा छुपाएँ |
| hideBottom | **bool** | नीचे का किनारा छुपाएँ |
| hideLeft | **bool** | बायाँ किनारा छुपाएँ |
| hideRight | **bool** | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | **bool** | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | **bool** | बॉर्डर बॉक्स लंबीय स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | **bool** | बॉर्डर बॉक्स नीचे-बाएँ से ऊपर-दाएँ तक स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | **bool** | बॉर्डर बॉक्स ऊपर-बाएँ से नीचे-दाएँ तक स्ट्राइकथ्रू |

### वापसी मान

नया बॉर्डर बॉक्स एलिमेंट

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)