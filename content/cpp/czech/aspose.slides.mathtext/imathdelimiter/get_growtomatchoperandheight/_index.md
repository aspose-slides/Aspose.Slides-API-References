---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou vertikálně, aby odpovídaly výšce jejich operandu. Výchozí hodnota je true
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() metoda


Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter. Když je true, oddělovače rostou vertikálně, aby odpovídaly výšce jejich operandu. Výchozí hodnota je true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
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