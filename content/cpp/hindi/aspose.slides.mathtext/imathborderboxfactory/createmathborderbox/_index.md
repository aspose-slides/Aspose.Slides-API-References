---
title: CreateMathBorderBox()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक गणितीय बॉर्डर बॉक्स बनाकर तत्व पर लागू करें
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) मेथड


एक गणितीय बॉर्डर बॉक्स बनाकर तत्व पर लागू करें

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बॉर्डर बॉक्स लागू करने के लिए गणितीय तत्व |

### Return Value

नया बॉर्डर बॉक्स एलिमेंट

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) मेथड


एक गणितीय बॉर्डर बॉक्स बनाकर तत्व पर लागू करें

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बॉर्डर बॉक्स लागू करने के लिए गणितीय तत्व |
| hideTop | **bool** | शीर्ष किनारा छुपाएँ |
| hideBottom | **bool** | निचला किनारा छुपाएँ |
| hideLeft | **bool** | बायाँ किनारा छुपाएँ |
| hideRight | **bool** | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | **bool** | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | **bool** | बॉर्डर बॉक्स ऊर्ध्वाधर स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | **bool** | बॉर्डर बॉक्स निचले-बाएँ से शीर्ष-दाएँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | **bool** | बॉर्डर बॉक्स शीर्ष-बाएँ से निचले-दाएँ स्ट्राइकथ्रू |

### Return Value

नया बॉर्डर बॉक्स एलिमेंट

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)