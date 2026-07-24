---
title: get_DelimiterShape()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn MathDelimiterShape::Centered ist, werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und passen sich weiterhin an die gesamte Höhe ihres Inhalts an. Wenn MathDelimiterShape::Match ist, werden ihre Höhe und Form exakt an ihren Inhalt angepasst."
type: docs
weight: 118
url: /de/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() Methode


Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn [MathDelimiterShape::Centered](../../mathdelimitershape/) ist, werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und passen sich weiterhin an die gesamte Höhe ihres Inhalts an. Wenn [MathDelimiterShape::Match](../../mathdelimitershape/) ist, werden ihre Höhe und Form exakt an ihren Inhalt angepasst.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Hinweise


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