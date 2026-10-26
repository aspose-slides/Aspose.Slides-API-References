---
title: get_Degree()
second_title: Aspose.Slides voor C++ API-referentie
description: Degree-argument
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathradical/get_degree/
---
## IMMathRadical::get_Degree() methode

Degree argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // kubuswortel
auto degreeElem = radical->get_Degree();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathRadical](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)