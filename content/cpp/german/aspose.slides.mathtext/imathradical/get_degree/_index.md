---
title: get_Degree()
second_title: Aspose.Slides für C++ API-Referenz
description: Grad-Argument
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() Methode


Degree Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Hinweise


Example: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // Kubikwurzel
auto degreeElem = radical->get_Degree();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathRadical](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)