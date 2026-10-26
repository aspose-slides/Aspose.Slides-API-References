---
title: set_DelimiterShape()
second_title: Aspose.Slides för C++ API-referens
description: "Anger formen på avgränsare i avgränsningsobjektet. När det är MathDelimiterShape::Centered, är avgränsare centrerade runt den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att fylla hela höjden av deras innehåll. När det är MathDelimiterShape::Match, ändras deras höjd och form för att exakt matcha deras innehåll."
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) metod

Anger formen på avgränsare i avgränsningsobjektet. När [MathDelimiterShape::Centered](../../mathdelimitershape/) är, avgränsare är centrerade runt den matematiska axeln i den matematiska texten och kan fortfarande anpassas så att de fyller hela höjden av deras innehåll. När [MathDelimiterShape::Match](../../mathdelimitershape/) är, ändras deras höjd och form för att exakt matcha deras innehåll.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Se även

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)