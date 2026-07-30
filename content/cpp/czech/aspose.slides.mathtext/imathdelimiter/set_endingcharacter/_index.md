---
title: set_EndingCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Delimiter Ending Character určuje koncový, nebo uzavírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'."
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) metoda


Delimiter Ending Character specifikuje koncový, nebo uzavírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky jako závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Viz také

* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)