---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: Functienaam Bijvoorbeeld zijn functienamen sin en cos
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() methode

Functienaam Bijvoorbeeld zijn functienamen sin en cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathFunction](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)