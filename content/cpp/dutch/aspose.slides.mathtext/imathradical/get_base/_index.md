---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-argument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() methode


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // kubuswortel
auto baseElem = radical->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathRadical](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)