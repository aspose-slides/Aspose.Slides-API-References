---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Specificerar tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer avgränsarna vertikalt för att matcha operandens höjd. Standardvärdet är true
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metod

Specificerar tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter När true, avgränsarna växer vertikalt för att matcha operandhöjden. Standardvärdet är true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Anmärkningar

Exempel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Se även

* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)