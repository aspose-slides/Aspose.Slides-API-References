---
title: set_DelimiterShape()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa kształt delimiterów w obiekcie delimiter. Gdy jest MathDelimiterShape::Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal dopasowywane do pełnej wysokości ich zawartości. Gdy jest MathDelimiterShape::Match, ich wysokość i kształt są zmieniane, aby dokładnie dopasować się do ich zawartości."
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) metoda

Określa kształt delimiterów w obiekcie delimiter. Gdy jest [MathDelimiterShape::Centered](../../mathdelimitershape/), delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal dopasowywane do pełnej wysokości ich zawartości. Gdy jest [MathDelimiterShape::Match](../../mathdelimitershape/), ich wysokość i kształt są zmieniane, aby dokładnie dopasować się do ich zawartości.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Zobacz także

* Wyliczenie [MathDelimiterShape](../../mathdelimitershape/)
* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)