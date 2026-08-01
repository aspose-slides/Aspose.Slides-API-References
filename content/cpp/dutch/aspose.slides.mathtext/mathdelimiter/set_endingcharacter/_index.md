---
title: set_EndingCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Ending Character specificeert het einde- of afsluitende scheidingsteken. Wiskundige scheidingstekens zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'."
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) methode


Delimiter Ending Character specificeert het einde- of afsluitende scheidingsteken. Wiskundige scheidingstekens zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
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