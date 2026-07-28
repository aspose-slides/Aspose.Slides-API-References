---
title: get_DelimiterShape()
second_title: Aspose.Slides C++ API hivatkozás
description: "Meghatározza a határolójelek alakját a delimiter objektumban. Ha MathDelimiterShape::Centered, a határolójelek középre vannak igazítva a matematikai szöveg matematikai tengelye körül, és még úgy is alakíthatók, hogy a tartalmuk teljes magasságának megfelelőek legyenek. Ha MathDelimiterShape::Match, magasságuk és alakjuk pontosan a tartalmukhoz igazodik."
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metódus

Meghatározza a határolójelek alakját a delimiter objektumban. Ha [MathDelimiterShape::Centered](../../mathdelimitershape/), a határolójelek a matematikai szöveg matematikai tengelye köré középre vannak igazítva, és még úgy is meg lehet őket alakítani, hogy megfeleljenek a tartalmuk teljes magasságának. Ha [MathDelimiterShape::Match](../../mathdelimitershape/), magasságuk és alakjuk pontosan a tartalmukhoz igazodik.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Megjegyzés

Példa:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Lásd még

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Osztály [MathDelimiter](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)