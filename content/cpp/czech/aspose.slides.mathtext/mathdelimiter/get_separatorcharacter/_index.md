---
title: get_SeparatorCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'."
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() metoda


Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
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