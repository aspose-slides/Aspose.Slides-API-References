---
title: set_SeparatorCharacter()
second_title: Aspose.Slides pro C++ – reference API
description: "Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí hodnota: '|'."
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metoda

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Poznámky

Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Viz také

* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)