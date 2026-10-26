---
title: set_DelimiterShape()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn MathDelimiterShape::Centered, werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und weiterhin so angepasst, dass sie die gesamte Höhe ihres Inhalts ausfüllen. Wenn MathDelimiterShape::Match, wird ihre Höhe und Form exakt an den Inhalt angepasst."
type: docs
weight: 131
url: /de/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) Methode

Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn [MathDelimiterShape::Centered](../../mathdelimitershape/), werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und weiterhin so angepasst, dass sie die gesamte Höhe ihres Inhalts ausfüllen. Wenn [MathDelimiterShape::Match](../../mathdelimitershape/), wird ihre Höhe und Form exakt an ihren Inhalt angepasst.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Anmerkungen

Beispiel:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Siehe auch

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)