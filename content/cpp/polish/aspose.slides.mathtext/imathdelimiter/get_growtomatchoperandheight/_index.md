---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides dla C++ Referencja API
description: Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandu. Domyślna wartość to true
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() metoda

Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandu. Domyślna wartość to true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Uwagi

Przykład: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Zobacz także

* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)