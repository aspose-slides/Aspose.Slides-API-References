---
title: set_BeginningCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Beginning Character specificeert het begin- of openingsscheidingsteken. Wiskundige scheidingstekens zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('."
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) methode


Delimiter Beginning Character specificeert het begin- of openingsscheidingsteken. Wiskundige scheidingstekens zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Opmerkingen


Voorbeeld:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Zie ook

* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)