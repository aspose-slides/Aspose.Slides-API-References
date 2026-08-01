---
title: ToMathArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst kindelementen in een verticale array
type: docs
weight: 235
url: /nl/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() methode

Plaatst kindelementen in een verticale array

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
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
* Klasse [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)