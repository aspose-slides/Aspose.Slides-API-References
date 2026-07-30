---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače se rozšiřují svisle tak, aby odpovídaly výšce operandu. Výchozí hodnota je true
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metoda

Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače se rozšiřují svisle tak, aby odpovídaly výšce operandu. Výchozí hodnota je true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
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