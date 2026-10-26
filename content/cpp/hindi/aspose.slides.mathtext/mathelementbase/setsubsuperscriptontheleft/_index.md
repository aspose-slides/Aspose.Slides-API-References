---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API संदर्भ
description: बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | सबसक्रिप्ट (बाएँ ओर निचला इंडेक्स) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | सुपरसक्रिप्ट (बाएँ ओर ऊपरी इंडेक्स) |

### रिटर्न मान

प्रकार [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method

बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### तर्क

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | सबसक्रिप्ट (बाएँ ओर निचला इंडेक्स) |
| superscript | [System::String](../../../system/string/) | सुपरसक्रिप्ट (बाएँ ओर ऊपरी इंडेक्स) |

### रिटर्न मान

प्रकार [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) का नया गणितीय तत्व

## टिप्पणी



उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)