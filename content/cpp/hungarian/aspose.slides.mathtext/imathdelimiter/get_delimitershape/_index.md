---
title: get_DelimiterShape()
second_title: Aspose.Slides C++ API referencia
description: "Meghatározza a határolójelek alakját a határolóobjektumban. Amikor MathDelimiterShape::Centered, a határolójelek a matematikai szöveg matematikai tengelye köré vannak középre helyezve, és úgy vannak méretezve, hogy az egész tartalmuk magasságát lefedjék. Amikor MathDelimiterShape::Match, magasságuk és alakjuk pontosan a tartalmukhoz igazodik."
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() method


Meghatározza a határolójelek alakját a határolóobjektumban. Amikor [MathDelimiterShape::Centered](../../mathdelimitershape/), a határolójelek a matematikai szöveg matematikai tengelye köré vannak középre helyezve, és úgy vannak méretezve, hogy az egész tartalmuk magasságát lefedjék. Amikor [MathDelimiterShape::Match](../../mathdelimitershape/), magasságuk és alakjuk pontosan a tartalmukhoz igazodik.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Lásd még

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Osztály [IMathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)