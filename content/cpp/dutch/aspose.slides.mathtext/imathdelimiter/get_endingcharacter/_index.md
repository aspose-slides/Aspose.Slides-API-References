---
title: get_EndingCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Ending Character specificeert het eind- of sluitteken van de delimiter. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'."
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() methode

Delimiter Ending Character specifies the ending, or closing, delimiter character. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaard: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
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