---
title: get_DelimiterShape()
second_title: Aspose.Slides för C++ API-referens
description: "Specificerar formen på avgränsare i avgränsningsobjektet. När är MathDelimiterShape::Centered, är avgränsarna centrerade kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att fylla hela höjden på deras innehåll. När är MathDelimiterShape::Match, ändras deras höjd och form för att exakt matcha deras innehåll."
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metod


Specificerar formen på avgränsare i avgränsningsobjektet. När är [MathDelimiterShape::Centered](../../mathdelimitershape/), är avgränsarna centrerade kring den matematiska axeln i den matematiska texten och kan fortfarande anpassas för att fylla hela höjden på deras innehåll. När är [MathDelimiterShape::Match](../../mathdelimitershape/), ändras deras höjd och form för att exakt matcha deras innehåll.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
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