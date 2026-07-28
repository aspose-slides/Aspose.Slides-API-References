---
title: get_DelimiterShape()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Określa kształt separatorów w obiekcie delimiter. Gdy jest MathDelimiterShape::Centered, separatory są wyśrodkowane wokół osi matematycznej tekstu i nadal mają dopasować się do całkowitej wysokości ich zawartości. Gdy jest MathDelimiterShape::Match, ich wysokość i kształt są zmieniane, aby dokładnie pasowały do ich zawartości."
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() metoda

Określa kształt separatorów w obiekcie delimiter. Gdy jest [MathDelimiterShape::Centered](../../mathdelimitershape/), separatory są wyśrodkowane wokół osi matematycznej tekstu i nadal mają dopasować się do całkowitej wysokości ich zawartości. Gdy jest [MathDelimiterShape::Match](../../mathdelimitershape/), ich wysokość i kształt są zmieniane, aby dokładnie pasowały do ich zawartości.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Uwagi

Przykład:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Zobacz także

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)