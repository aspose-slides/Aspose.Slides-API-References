---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) विधि


दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the right) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (upper index on the right) |

### रिटर्न मान

प्रकार [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) का नया गणितीय तत्व
## टिप्पणी



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) विधि


दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### रिटर्न मान

प्रकार [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) का नया गणितीय तत्व
## टिप्पणी



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)