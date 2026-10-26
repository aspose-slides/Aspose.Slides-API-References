---
title: get_EndingCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Delimiter Ending Character specifikuje koncový, nebo uzavírací znak ohraničení. Matematické ohraničovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: ')'."
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() metoda


Delimiter Ending Character specifikuje koncový, nebo uzavírací znak ohraničení. Matematické ohraničovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
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