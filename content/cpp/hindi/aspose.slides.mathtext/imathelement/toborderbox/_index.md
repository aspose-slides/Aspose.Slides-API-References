---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API संदर्भ
description: इस तत्व को बॉर्डर-बॉक्स में रखता है
type: docs
weight: 261
url: /hi/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() मेथड

इस तत्व को बॉर्डर-बॉक्स में रखता है

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### वापसी मान

इस तत्व को अंदर रखे हुए बॉर्डर-बॉक्स
## टिप्पणियाँ



उदाहरण: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) मेथड

इस तत्व को बॉर्डर-बॉक्स में रखता है

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | वर्णन |
| --- | --- | --- |
| hideTop | **bool** | ऊपर किनारा छुपाएँ |
| hideBottom | **bool** | नीचे किनारा छुपाएँ |
| hideLeft | **bool** | बायाँ किनारा छुपाएँ |
| hideRight | **bool** | दायाँ किनारा छुपाएँ |
| strikethroughHorizontal | **bool** | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | **bool** | बॉर्डर बॉक्स लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | **bool** | बॉर्डर बॉक्स नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | **bool** | बॉर्डर बॉक्स ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू |

### वापसी मान

इस तत्व को अंदर रखे हुए बॉर्डर-बॉक्स
## टिप्पणियाँ



उदाहरण: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBorderBox](../../imathborderbox/)
* क्लास [IMathElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)