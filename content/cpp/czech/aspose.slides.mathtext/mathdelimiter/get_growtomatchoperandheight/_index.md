---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje růst BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače se vertikálně rozšiřují tak, aby odpovídaly výšce operandu. Výchozí hodnota je true
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() metoda

Určuje růst BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače se vertikálně rozšiřují tak, aby odpovídaly výšce operandu. Výchozí hodnota je true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Poznámky

Příklad: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Viz také

* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)