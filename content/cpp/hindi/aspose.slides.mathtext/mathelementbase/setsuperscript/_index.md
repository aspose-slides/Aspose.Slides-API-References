---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API संदर्भ
description: उपरि सूचक बनाता है
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) विधि


उपरि सूचक बनाता है

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (right side upper index) |

### रिटर्न मान

प्रकार [IMathSuperscriptElement](../../imathsuperscriptelement/) का नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) विधि


उपरि सूचक बनाता है

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superscript (right side upper index) |

### रिटर्न मान

प्रकार [IMathSuperscriptElement](../../imathsuperscriptelement/) का नया गणित तत्व

## टिप्पणियाँ



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathSuperscriptElement](../../imathsuperscriptelement/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)