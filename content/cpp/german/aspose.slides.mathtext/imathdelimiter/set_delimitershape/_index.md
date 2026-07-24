---
title: set_DelimiterShape()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt die Form der Trennzeichen im Trennzeichenobjekt fest. Wenn MathDelimiterShape::Centered, werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und passen sich dennoch an die gesamte Höhe ihres Inhalts an. Wenn MathDelimiterShape::Match, werden Höhe und Form so geändert, dass sie exakt ihrem Inhalt entsprechen."
type: docs
weight: 131
url: /de/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) Methode

Gibt die Form der Trennzeichen im Trennzeichenobjekt an. Wenn [MathDelimiterShape::Centered](../../mathdelimitershape/), werden die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert und passen sich dennoch an die gesamte Höhe ihres Inhalts an. Wenn [MathDelimiterShape::Match](../../mathdelimitershape/), werden Höhe und Form so angepasst, dass sie exakt ihrem Inhalt entsprechen.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Bemerkungen

Beispiel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Siehe auch

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)