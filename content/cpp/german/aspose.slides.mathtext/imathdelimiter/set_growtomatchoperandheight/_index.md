---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Wachstum von BeginningCharacter, SeparatorCharacter und EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true
type: docs
weight: 105
url: /de/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) Methode

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter und EndingCharacter an. Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen. Der Standardwert ist true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Bemerkungen

Beispiel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Siehe auch

* Klasse [IMathDelimiter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)