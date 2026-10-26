---
title: get_Degree()
second_title: Aspose.Slides voor C++ API-referentie
description: Graadargument
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() methode


Graadargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Opmerkingen


Voorbeeld:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathRadical](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)