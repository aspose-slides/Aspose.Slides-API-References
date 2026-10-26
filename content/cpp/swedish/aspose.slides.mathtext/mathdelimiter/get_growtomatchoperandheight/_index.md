---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer avgränsarna vertikalt för att matcha sin operandhöjd. Standardvärdet är true
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() metod


Anger tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer avgränsarna vertikalt för att matcha sin operandhöjd. Standardvärdet är true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
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