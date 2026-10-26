---
title: get_SeparatorCharacter()
second_title: Odwołanie API Aspose.Slides dla C++
description: "Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'."
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() metoda

Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
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