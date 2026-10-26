---
title: set_EndingCharacter()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Delimiter Ending Character určuje koncový, nebo uzavírací, znak oddělovače. Matematické oddělovače jsou obalující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'."
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) metoda

Delimiter Ending Character určuje koncový, nebo uzavírací, znak oddělovače. Matematické oddělovače jsou obalující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
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