---
title: get_Base()
second_title: Aspose.Slides के लिए C++ एपीआई संदर्भ
description: एक्सेंट लागू किए गए तर्क
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() विधि


एक्सेंट लागू किए गए तर्क

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathAccent](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)