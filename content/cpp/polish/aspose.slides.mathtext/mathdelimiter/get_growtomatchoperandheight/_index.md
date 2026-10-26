---
title: get_GrowToMatchOperandHeight()
second_title: Odniesienie API Aspose.Slides dla C++
description: Określa wzrost znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. Domyślna wartość to true
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() metoda


Określa wzrost znaków BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandów. Domyślna wartość to true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Zobacz także

* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)