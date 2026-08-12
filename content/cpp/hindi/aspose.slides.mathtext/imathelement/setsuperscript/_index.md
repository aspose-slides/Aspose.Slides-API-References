---
title: SetSuperscript()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सुपरस्क्रिप्ट बनाता है
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) विधि

सुपरस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | सुपरस्क्रिप्ट (दाएँ ऊपर वाला सूचकांक) |

### रिटर्न मान

प्रकार [IMathSuperscriptElement](../../imathsuperscriptelement/) का नया गणित तत्व

## टिप्पणी

उदाहरण:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) विधि

सुपरस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### आर्गुमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | सुपरस्क्रिप्ट (दाएँ ऊपर वाला सूचकांक) |

### रिटर्न मान

प्रकार [IMathSuperscriptElement](../../imathsuperscriptelement/) का नया गणित तत्व

## टिप्पणी

उदाहरण:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathSuperscriptElement](../../imathsuperscriptelement/)
* क्लास [IMathElement](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)