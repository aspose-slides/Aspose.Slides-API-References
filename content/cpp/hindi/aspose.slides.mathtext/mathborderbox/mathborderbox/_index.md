---
title: MathBorderBox()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: आयताकार बॉर्डर वाला MathBorderBox तत्व बनाता है
type: docs
weight: 222
url: /hi/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) कंस्ट्रक्टर

एक आयताकार बॉर्डर के साथ [MathBorderBox](../) तत्व बनाता है

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ऐसी बेस तत्व जिसके ऊपर बॉर्डर बॉक्स लागू होता है। null हो सकता है। |

## टिप्पणी

उदाहरण: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) कंस्ट्रक्टर

[MathBorderBox](../) तत्व बनाता है

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ऐसी बेस तत्व जिसके ऊपर बॉर्डर बॉक्स लागू होता है |
| hideTop | **bool** | ऊपरी किनारा छिपाएँ |
| hideBottom | **bool** | निचला किनारा छिपाएँ |
| hideLeft | **bool** | बायाँ किनारा छिपाएँ |
| hideRight | **bool** | दायाँ किनारा छिपाएँ |
| strikethroughHorizontal | **bool** | क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | **bool** | ऊर्ध्वाधर स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | **bool** | निचले-बाएँ से ऊपरी-दाएँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | **bool** | ऊपरी-बाएँ से निचले-दाएँ स्ट्राइकथ्रू |

## टिप्पणी

उदाहरण: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## संबंधित देखें

* प्रकारपरिभाषा [SharedPtr](../../../system/sharedptr/)
* वर्ग [IMathElement](../../imathelement/)
* वर्ग [MathBorderBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)