---
title: ToMathArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst in een verticale array
type: docs
weight: 170
url: /nl/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() methode

Plaatst in een verticale array

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```

### Retourwaarde

Nieuwe instantie van type [IMathArray](../../imatharray/)
## Opmerkingen



Voorbeeld: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathArray](../../imatharray/)
* Klasse [MathElementBase](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)