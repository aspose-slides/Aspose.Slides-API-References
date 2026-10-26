---
title: set_SeparatorCharacter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'."
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metoda


Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Zobacz także

* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)