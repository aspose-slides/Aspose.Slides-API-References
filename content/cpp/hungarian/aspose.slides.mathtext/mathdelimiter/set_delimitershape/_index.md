---
title: set_DelimiterShape()
second_title: Aspose.Slides C++ API-referencia
description: "Megadja a határolók alakját a határoló objektumban. Ha MathDelimiterShape::Centered, a határolók a matematikai szöveg matematikai tengelye köré vannak középre igazítva, és továbbra is a tartalmuk teljes magasságához igazíthatók. Ha MathDelimiterShape::Match, magasságuk és alakjuk pontosan a tartalmukhoz igazodik."
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) metódus


Meghatározza a határolók alakját a határoló objektumban. Amikor [MathDelimiterShape::Centered](../../mathdelimitershape/), a határolók a matematikai szöveg matematikai tengelye köré vannak középre igazítva, és továbbra is a tartalmuk teljes magasságához igazíthatók. Amikor [MathDelimiterShape::Match](../../mathdelimitershape/), magasságuk és alakjuk pontosan a tartalmukhoz igazodik.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Lásd még

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)