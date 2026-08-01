---
title: get_BeginningCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Beginning Character specificeert het begin- of openingsteken. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaardwaarde: '('."
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() methode

Delimiter Beginning Character specificeert het begin- of openingsteken. Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades. Standaardwaarde: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
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