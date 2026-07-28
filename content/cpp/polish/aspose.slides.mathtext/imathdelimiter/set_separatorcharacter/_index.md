---
title: set_SeparatorCharacter()
second_title: Aspose.Slides dla C++ Referencja API
description: "Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'."
type: docs
weight: 53
url: /pl/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metoda


Delimiter Separator Character określa znak, który oddziela argumenty w obiekcie delimiter. Domyślnie: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
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