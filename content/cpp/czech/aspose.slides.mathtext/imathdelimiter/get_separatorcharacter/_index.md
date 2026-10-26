---
title: get_SeparatorCharacter()
second_title: Aspose.Slides pro C++ API referenci
description: "Delimiter Separator Character specifikuje znak, který odděluje argumenty v objektu delimiteru. Výchozí: '|'."
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metoda


Delimiter Separator Character specifikuje znak, který odděluje argumenty v objektu delimiteru. Výchozí: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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