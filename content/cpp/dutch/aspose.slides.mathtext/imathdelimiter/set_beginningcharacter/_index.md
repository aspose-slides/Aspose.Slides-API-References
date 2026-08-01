---
title: set_BeginningCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Beginning Character specificeert het begin- of openings-delimiterteken. Wiskundige delimiters zijn omhullende tekens zoals haakjes, vierkante haken en accolades. De standaardwaarde: '('."
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) methode

Delimiter Beginning Character specificeert het begin- of openings-delimiterteken. Wiskundige delimiters zijn omhullende tekens zoals haakjes, vierkante haken en accolades. De standaardwaarde: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Zie ook

* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)