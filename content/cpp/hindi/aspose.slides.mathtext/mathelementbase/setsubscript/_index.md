---
title: SetSubscript()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सबस्क्रिप्ट बनाता है
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) मेथड


Creates subscript

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (right side lower index) |

### रिटर्न वैल्यू

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## टिप्पणियाँ



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) मेथड


Creates subscript

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (right side lower index) |

### रिटर्न वैल्यू

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)
## टिप्पणियाँ



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathSubscriptElement](../../imathsubscriptelement/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathElementBase](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)