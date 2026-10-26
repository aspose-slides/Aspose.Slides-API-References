---
title: ToBorderBox()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: इस तत्व को बॉर्डर बॉक्स में रखता है
type: docs
weight: 248
url: /hi/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() विधि


इस तत्व को बॉर्डर-बॉक्स में रखता है

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### रिटर्न मान

इस तत्व को अंदर रखे हुए बॉर्डर-बॉक्स
## टिप्पणी



उदाहरण: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) विधि


इस तत्व को बॉर्डर-बॉक्स में रखता है

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hideTop | **bool** | ऊपर का किनारा छुपाएँ |
| hideBottom | **bool** | नीचे का किनारा छुपाएँ |
| hideLeft | **bool** | बाएँ किनारा छुपाएँ |
| hideRight | **bool** | दाएँ किनारा छुपाएँ |
| strikethroughHorizontal | **bool** | बॉर्डर बॉक्स क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | **bool** | बॉर्डर बॉक्स लंबवत स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | **bool** | बॉर्डर बॉक्स स्ट्राइकथ्रू निचले-बाएँ से ऊपर-दाएँ |
| strikethroughTopLeftToBottomRight | **bool** | बॉर्डर बॉक्स स्ट्राइकथ्रू ऊपर-बाएँ से निचले-दाएँ |

### रिटर्न मान

इस तत्व को अंदर रखे हुए बॉर्डर-बॉक्स
## टिप्पणी



उदाहरण: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBorderBox](../../imathborderbox/)
* क्लास [MathElementBase](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)