---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um ihre Operandhöhe anzupassen. Der Standardwert ist true
type: docs
weight: 92
url: /de/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() Methode


Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um ihre Operandhöhe anzupassen. Der Standardwert ist true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Anmerkungen


Beispiel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Siehe Auch

* Klasse [MathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)