---
title: get_Base()
second_title: Aspose.Slides voor C++ API Referentie
description: Basisargument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() methode


Basisargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Opmerkingen



Voorbeeld: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)