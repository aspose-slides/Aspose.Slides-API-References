---
title: set_SeparatorCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Separator Character specificeert het teken dat de argumenten scheidt in het delimiter-object. Standaard: '|'."
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) methode

Delimiter Separator Character specificeert het teken dat de argumenten scheidt in het delimiter-object. Standaard: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Zie ook

* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)