---
title: SetSubscript()
second_title: Aspose.Slides for C++ API संदर्भ
description: सबस्क्रिप्ट बनाता है
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) विधि

सबस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | सबस्क्रिप्ट (दाईं ओर नीचे का सूचकांक) |

### वापसी मान

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## टिप्पणी



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) विधि

सबस्क्रिप्ट बनाता है

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | सबस्क्रिप्ट (दाईं ओर नीचे का सूचकांक) |

### वापसी मान

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## टिप्पणी



उदाहरण: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathSubscriptElement](../../imathsubscriptelement/)
* क्लास [IMathElement](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)