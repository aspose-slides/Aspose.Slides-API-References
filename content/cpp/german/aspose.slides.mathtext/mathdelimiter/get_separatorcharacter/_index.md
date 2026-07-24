---
title: get_SeparatorCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: "Delimiter Separator Character gibt das Zeichen an, das Argumente im Delimiter-Objekt trennt. Der Standardwert: '|'."
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() Methode

Delimiter Separator Character gibt das Zeichen an, das Argumente im Delimiter-Objekt trennt. Der Standardwert: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```
## Anmerkungen

Beispiel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```
## Siehe auch

* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)