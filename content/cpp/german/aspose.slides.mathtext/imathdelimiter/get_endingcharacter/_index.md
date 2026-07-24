---
title: get_EndingCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: "Delimiter Ending Character gibt das abschließende, oder schließende, Trennzeichenzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: ')'."
type: docs
weight: 66
url: /de/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() Methode


Delimiter Ending Character gibt das abschließende, oder schließende, Trennzeichenzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Bemerkungen


Beispiel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Siehe auch

* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)