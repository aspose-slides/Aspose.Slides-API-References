---
title: get_BeginningCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: "Delimiter Beginning Character spezifiziert das Anfangs- bzw. Öffnungszeichen des Trennzeichens. Mathematische Trennzeichen sind einrahmende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('."
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() Methode

Delimiter Beginning Character spezifiziert das Anfangs- oder Öffnungszeichen des Trennzeichens. Mathematische Trennzeichen sind einrahmende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern. Der Standardwert: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Anmerkungen

Beispiel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Siehe auch

* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)