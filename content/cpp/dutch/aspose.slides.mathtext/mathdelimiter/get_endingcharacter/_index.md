---
title: get_EndingCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Ending Character specificeert het eind- of sluitingskarakter van de delimiter. Wiskundige delimiters zijn omhullende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'."
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() methode

Delimiter Ending Character specificeert het eind- of sluitingskarakter van de delimiter. Wiskundige delimiters zijn omhullende tekens zoals haakjes, vierkante haken en accolades. De standaard: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```
## Opmerkingen

Voorbeeld:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```
## Zie ook

* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)