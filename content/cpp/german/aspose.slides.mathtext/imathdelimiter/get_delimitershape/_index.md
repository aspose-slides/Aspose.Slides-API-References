---
title: get_DelimiterShape()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt die Form der Trennzeichen im Trennzeichen-Objekt an. Wenn MathDelimiterShape::Centered, werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und so angepasst, dass sie die gesamte Höhe ihres Inhalts ausfüllen. Wenn MathDelimiterShape::Match, werden ihre Höhe und Form exakt an ihren Inhalt angepasst."
type: docs
weight: 118
url: /de/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() Methode


Gibt die Form der Trennzeichen im Trennzeichen-Objekt an. Wenn [MathDelimiterShape::Centered](../../mathdelimitershape/), werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und so angepasst, dass sie die gesamte Höhe ihres Inhalts ausfüllen. Wenn [MathDelimiterShape::Match](../../mathdelimitershape/), werden ihre Höhe und Form exakt an ihren Inhalt angepasst.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Anmerkungen


Beispiel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Siehe auch

* Aufzählung [MathDelimiterShape](../../mathdelimitershape/)
* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)