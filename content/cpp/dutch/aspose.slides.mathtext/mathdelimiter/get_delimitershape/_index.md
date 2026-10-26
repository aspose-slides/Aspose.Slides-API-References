---
title: get_DelimiterShape()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert de vorm van scheidingstekens in het scheidingstekenobject. Wanneer MathDelimiterShape::Centered is, worden scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en passen ze zich nog steeds aan om de volledige hoogte van hun inhoud te bestrijken. Wanneer MathDelimiterShape::Match is, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud."
type: docs
weight: 118
url: /nl/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() methode

Specificeert de vorm van scheidingstekens in het scheidingstekenobject. Wanneer [MathDelimiterShape::Centered](../../mathdelimitershape/) is, worden scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en passen ze zich nog steeds aan om de volledige hoogte van hun inhoud te bestrijken. Wanneer [MathDelimiterShape::Match](../../mathdelimitershape/) is, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Opmerkingen

Voorbeeld:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Zie ook

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)