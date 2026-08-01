---
title: set_DelimiterShape()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specificeert de vorm van scheidingstekens in het delimiter-object. Wanneer MathDelimiterShape::Centered is, worden scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en nog steeds aangepast om de volledige hoogte van hun inhoud te passen. Wanneer MathDelimiterShape::Match is, worden hun hoogte en vorm aangepast om precies aan hun inhoud te voldoen."
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) methode


Specificeert de vorm van scheidingstekens in het delimiter-object. Wanneer [MathDelimiterShape::Centered](../../mathdelimitershape/) is, worden scheidingstekens gecentreerd rond de wiskunde-as van de wiskundige tekst en nog steeds aangepast om de volledige hoogte van hun inhoud te passen. Wanneer [MathDelimiterShape::Match](../../mathdelimitershape/) is, worden hun hoogte en vorm aangepast om precies aan hun inhoud te voldoen.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
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