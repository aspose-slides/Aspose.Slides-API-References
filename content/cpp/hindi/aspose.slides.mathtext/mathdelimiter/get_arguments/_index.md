---
title: get_Arguments()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक या अधिक गणितीय तत्व जो डिलिमिटर वर्णों द्वारा अलग किए गए हैं
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() विधि


One or more mathematical elements separated by delimiter characters

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElementCollection](../../imathelementcollection/)
* क्लास [MathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)