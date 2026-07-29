---
title: get_DelimiterShape()
second_title: Aspose.Slides för C++ API-referens
description: "Anger formen på avgränsare i avgränsare-objektet. När är MathDelimiterShape::Centered, centreras avgränsarna kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas så att de fyller hela höjden på deras innehåll. När är MathDelimiterShape::Match, ändras deras höjd och form så att de exakt matchar deras innehåll."
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() metod

Anger formen på avgränsare i avgränsare-objektet. När [MathDelimiterShape::Centered](../../mathdelimitershape/) är, centreras avgränsarna kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas så att de fyller hela höjden på deras innehåll. När [MathDelimiterShape::Match](../../mathdelimitershape/) är, ändras deras höjd och form så att de exakt motsvarar deras innehåll.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Se även

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)