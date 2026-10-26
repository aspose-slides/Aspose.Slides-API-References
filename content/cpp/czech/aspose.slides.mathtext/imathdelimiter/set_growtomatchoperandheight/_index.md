---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače se rozšiřují vertikálně tak, aby odpovídaly výšce operandu. Výchozí hodnota je true
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) metoda


Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače se rozšiřují vertikálně tak, aby odpovídaly výšce operandu. Výchozí hodnota je true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Poznámky


Příklad:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Viz také

* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)