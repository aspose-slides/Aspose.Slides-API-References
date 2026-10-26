---
title: ToMathArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst in een verticale array
type: docs
weight: 183
url: /nl/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() methode


Plaatst in een verticale array

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
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
* Klasse [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)