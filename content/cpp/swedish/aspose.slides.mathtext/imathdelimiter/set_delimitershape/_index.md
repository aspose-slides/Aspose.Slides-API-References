---
title: set_DelimiterShape()
second_title: Aspose.Slides för C++ API-referens
description: "Anger formen på avgränsare i avgränsningsobjektet. När MathDelimiterShape::Centered är avgränsarna centrerade kring den matematiska axeln i den matematiska texten och ändå anpassas för att fylla hela höjden på deras innehåll. När MathDelimiterShape::Match är deras höjd och form ändrade för att exakt matcha deras innehåll."
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) method

Anger formen på avgränsare i avgränsningsobjektet. När [MathDelimiterShape::Centered](../../mathdelimitershape/) är avgränsarna centrerade kring den matematiska axeln i den matematiska texten och ändå anpassas för att fylla hela höjden på deras innehåll. När [MathDelimiterShape::Match](../../mathdelimitershape/) är deras höjd och form ändras för att exakt matcha deras innehåll.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
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