---
title: get_SeparatorCharacter()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Separator delimitera określa znak, który oddziela argumenty w obiekcie delimitera. Domyślnie: '|'."
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metoda

Separator delimitera określa znak, który oddziela argumenty w obiekcie delimitera. Domyślnie: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Uwagi

Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Zobacz także

* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)