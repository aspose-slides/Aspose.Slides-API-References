---
title: get_BeginningCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Beginning Character specificeert het begin- of opening-teken van de delimiter. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haakjes en accolades. Standaard: '('."
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() methode


Delimiter Beginning Character specificeert het begin- of opening-teken van de delimiter. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haakjes en accolades. Standaard: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
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