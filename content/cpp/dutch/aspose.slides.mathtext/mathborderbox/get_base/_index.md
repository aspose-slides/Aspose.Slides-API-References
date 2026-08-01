---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Base argument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() methode


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBorderBox](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)