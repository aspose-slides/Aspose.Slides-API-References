---
title: get_Degree()
second_title: Aspose.Slides für C++ API-Referenz
description: Grad-Argument
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() Methode


Grad-Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Bemerkungen


Beispiel: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathRadical](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)