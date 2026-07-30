---
title: set_SeparatorCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Delimiter Separator Character specifikuje znak, který odděluje argumenty v objektu delimiter. Výchozí: '|'."
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metoda

Delimiter Separator Character specifikuje znak, který odděluje argumenty v objektu delimiter. Výchozí: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Viz také

* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)