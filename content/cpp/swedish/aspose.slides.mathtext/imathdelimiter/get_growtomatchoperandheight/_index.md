---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer avgränsarna vertikalt för att matcha dess operandhöjd. Standardvärdet är true
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() metod


Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter När true, växer avgränsarna vertikalt för att matcha dess operandhöjd. Standardvärdet är true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Anmärkningar


Exempel:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Se också

* Klass [IMathDelimiter](../)
* Namnutrymme [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)