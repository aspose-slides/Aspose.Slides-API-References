---
title: get_SeparatorCharacter()
second_title: Aspose.Slides voor C++ API Referentie
description: "Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. Standaard: '|'."
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() methode


Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter object. Standaard: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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