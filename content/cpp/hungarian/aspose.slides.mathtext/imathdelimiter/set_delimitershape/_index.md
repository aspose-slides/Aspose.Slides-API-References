---
title: set_DelimiterShape()
second_title: Aspose.Slides C++ API referencia
description: "Meghatározza a határolók alakját a határoló objektumban. Ha MathDelimiterShape::Centered, a határolók a matematikai szöveg matematikai tengelye köré vannak középre helyezve, és úgy készülnek, hogy a teljes magasságuk illeszkedjen a tartalmukhoz. Ha MathDelimiterShape::Match, magasságuk és alakjuk pontosan a tartalmukhoz igazodik."
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) metódus


Meghatározza a határolók alakját a határoló objektumban. Amikor [MathDelimiterShape::Centered](../../mathdelimitershape/), a határolók a matematikai szöveg matematikai tengelye köré középre vannak helyezve, és úgy készülnek, hogy a teljes magasságuk illeszkedjen a tartalmukhoz. Amikor [MathDelimiterShape::Match](../../mathdelimitershape/), magasságuk és alakjuk pontosan a tartalmukhoz igazodik.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
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
* Könyvtár [Aspose.Slides](../../../)