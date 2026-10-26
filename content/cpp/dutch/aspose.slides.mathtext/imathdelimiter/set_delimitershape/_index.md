---
title: set_DelimiterShape()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert de vorm van scheidingstekens in het delimiter-object. Wanneer MathDelimiterShape::Centered is, worden scheidingstekens gecentreerd rond de wiskundige as van de wiskundige tekst en moeten ze nog steeds zo worden gemaakt dat ze de volledige hoogte van hun inhoud passen. Wanneer MathDelimiterShape::Match is, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud."
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) methode

Specificeert de vorm van scheidingstekens in het delimiter-object. Wanneer [MathDelimiterShape::Centered](../../mathdelimitershape/) is, worden scheidingstekens gecentreerd rond de wiskundige as van de wiskundige tekst en moeten ze nog steeds zo worden gemaakt dat ze de volledige hoogte van hun inhoud passen. Wanneer [MathDelimiterShape::Match](../../mathdelimitershape/) is, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Zie ook

* Enumeratie [MathDelimiterShape](../../mathdelimitershape/)
* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)