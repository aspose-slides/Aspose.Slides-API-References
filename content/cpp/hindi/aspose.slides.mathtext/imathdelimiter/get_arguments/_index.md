---
title: get_Arguments()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक या अधिक गणितीय तत्व जिन्हें डिलिमीटर वर्णों द्वारा अलग किया गया है
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() विधि


एक या अधिक गणितीय तत्व जिन्हें डिलिमीटर वर्णों द्वारा अलग किया गया है

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
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
* क्लास [IMathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)