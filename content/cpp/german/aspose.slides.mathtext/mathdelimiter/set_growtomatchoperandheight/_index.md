---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wächst der Delimiter vertikal, um seine Operand-Höhe zu entsprechen. Der Standardwert ist true
type: docs
weight: 105
url: /de/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) Methode

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wächst der Delimiter vertikal, um seine Operand-Höhe zu entsprechen. Der Standardwert ist true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Hinweise

Beispiel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Siehe auch

* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)