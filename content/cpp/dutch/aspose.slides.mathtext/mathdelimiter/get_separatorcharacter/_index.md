---
title: get_SeparatorCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. Standaard: '|'."
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() methode


Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. Standaard: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Zie ook

* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)