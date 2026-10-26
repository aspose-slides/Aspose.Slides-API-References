---
title: get_BeginningCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: "Delimiter Beginning Character gibt den Anfangs- oder öffnenden Trennzeichencharakter an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('."
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() Methode


Delimiter Beginning Character gibt das Anfangs- bzw. öffnende Trennzeichen an. Mathematische Trennzeichen sind umschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Hinweise


Beispiel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Siehe auch

* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)