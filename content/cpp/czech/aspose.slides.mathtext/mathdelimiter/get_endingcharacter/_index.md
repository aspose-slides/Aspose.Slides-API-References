---
title: get_EndingCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Delimiter Ending Character určuje ukončovací, nebo závěrečný, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: ')'."
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metoda


Koncový znak oddělovače určuje ukončovací, nebo závěrečný, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Viz také

* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)