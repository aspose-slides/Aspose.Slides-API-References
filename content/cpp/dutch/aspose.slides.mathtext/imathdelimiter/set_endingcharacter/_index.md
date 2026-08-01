---
title: set_EndingCharacter()
second_title: Aspose.Slides voor C++ API Referentie
description: "Delimiter Ending Character specificeert het eind- of sluitteken. Wiskundige scheidingstekens zijn omhullende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'."
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) methode


Delimiter Ending Character specificeert het eind- of sluitteken. Wiskundige scheidingstekens zijn omhullende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Zie ook

* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)