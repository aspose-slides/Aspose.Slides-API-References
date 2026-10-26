---
title: get_DelimiterShape()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Określa kształt delimiterów w obiekcie delimiter. Gdy jest MathDelimiterShape::Centered, delimitery są wyśrodkowane wokół osi matematycznej tekstu matematycznego i nadal mogą być dopasowane do całej wysokości ich zawartości. Gdy jest MathDelimiterShape::Match, ich wysokość i kształt są zmieniane, aby dokładnie pasowały do ich zawartości."
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metoda

Określa kształt delimiterów w obiekcie delimiter. Gdy jest [MathDelimiterShape::Centered](../../mathdelimitershape/), delimitery są wyśrodkowane wokół osi matematycznej tekstu matematycznego i nadal mogą być dopasowane do całej wysokości ich zawartości. Gdy jest [MathDelimiterShape::Match](../../mathdelimitershape/), ich wysokość i kształt są zmieniane, aby dokładnie odpowiadały ich zawartości.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
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