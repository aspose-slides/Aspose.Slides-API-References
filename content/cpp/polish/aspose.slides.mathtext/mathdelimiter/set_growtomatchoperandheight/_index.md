---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ – odniesienie do API
description: Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandu. Domyślna wartość to true
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metoda

Określa wzrost BeginningCharacter, SeparatorCharacter, EndingCharacter. Gdy wartość jest true, delimitery rosną pionowo, aby dopasować się do wysokości ich operandu. Domyślna wartość to true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
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