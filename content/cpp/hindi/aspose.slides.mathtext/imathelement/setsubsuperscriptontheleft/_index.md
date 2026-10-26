---
title: SetSubSuperscriptOnTheLeft()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) विधि


बायीं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (बायीं ओर निचला अनुक्रमांक) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (बायीं ओर ऊपरी अनुक्रमांक) |

### रिटर्न वैल्यू

नया गणित तत्व प्रकार [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## टिप्पणी



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) विधि


बायीं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (बायीं ओर निचला अनुक्रमांक) |
| superscript | [System::String](../../../system/string/) | Superscript (बायीं ओर ऊपरी अनुक्रमांक) |

### रिटर्न वैल्यू

नया गणित तत्व प्रकार [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## टिप्पणी



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## साथ देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* क्लास [IMathElement](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)