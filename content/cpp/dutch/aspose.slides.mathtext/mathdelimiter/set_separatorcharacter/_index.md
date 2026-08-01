---
title: set_SeparatorCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: "Delimiter Separator Character geeft het teken aan dat de argumenten scheidt in het delimiter-object. Standaard: '|'."
type: docs
weight: 53
url: /nl/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) methode


Delimiter Separator Character geeft het teken aan dat de argumenten scheidt in het delimiter-object. Standaard: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
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
* Bibliotheek [Aspose.Slides](../../../)