---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true
type: docs
weight: 92
url: /de/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() Methode

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Hinweise

Beispiel:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Siehe auch

* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)