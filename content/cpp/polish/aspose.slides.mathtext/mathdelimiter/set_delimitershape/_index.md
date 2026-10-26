---
title: set_DelimiterShape()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Określa kształt delimiterów w obiekcie delimiter. Gdy jest MathDelimiterShape::Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal dopasowywane do całkowitej wysokości ich zawartości. Gdy jest MathDelimiterShape::Match, ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do ich zawartości."
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) metoda

Określa kształt delimiterów w obiekcie delimiter. Gdy jest [MathDelimiterShape::Centered](../../mathdelimitershape/), delimitery są wyśrodkowane wokół osi matematycznej tekstu i nadal dopasowywane do całkowitej wysokości ich zawartości. Gdy jest [MathDelimiterShape::Match](../../mathdelimitershape/), ich wysokość i kształt są zmieniane tak, aby dokładnie pasowały do ich zawartości.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Uwagi

Przykład:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Zobacz także

* Wyliczenie [MathDelimiterShape](../../mathdelimitershape/)
* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)