---
title: get_DelimiterShape()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specifieert de vorm van scheidingstekens in het scheidingstekenobject. Wanneer MathDelimiterShape::Centered is, worden scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en nog steeds aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape::Match is, worden hun hoogte en vorm aangepast zodat ze precies overeenkomen met hun inhoud."
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() method


Specificeert de vorm van scheidingstekens in het scheidingstekenobject. Wanneer [MathDelimiterShape::Centered](../../mathdelimitershape/) is, worden scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en nog steeds aangepast om de volledige hoogte van hun inhoud te passen. Wanneer [MathDelimiterShape::Match](../../mathdelimitershape/) is, worden hun hoogte en vorm aangepast zodat ze precies overeenkomen met hun inhoud.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Zie ook

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)