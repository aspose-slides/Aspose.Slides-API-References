---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer avgränsarna vertikalt för att matcha sin operandhöjd. Standardvärdet är true
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) metod


Anger tillväxten av BeginningCharacter, SeparatorCharacter, EndingCharacter. När true växer avgränsarna vertikalt för att matcha dess operandhöjd. Standardvärdet är true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Anmärkningar


Exempel: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Se också

* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)