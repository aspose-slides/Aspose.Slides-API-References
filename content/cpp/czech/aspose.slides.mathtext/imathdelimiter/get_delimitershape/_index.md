---
title: get_DelimiterShape()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Definuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape::Centered, jsou oddělovače vycentrovány kolem matematické osy matematického textu a jsou upraveny tak, aby odpovídaly celé výšce jejich obsahu. Když je MathDelimiterShape::Match, jejich výška a tvar jsou změněny tak, aby přesně odpovídaly jejich obsahu."
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() metoda

Specifikuje tvar oddělovačů v objektu oddělovače. Když je [MathDelimiterShape::Centered](../../mathdelimitershape/), jsou oddělovače vycentrovány kolem matematické osy matematického textu a stále jsou upraveny tak, aby odpovídaly celé výšce jejich obsahu. Když je [MathDelimiterShape::Match](../../mathdelimitershape/), jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Viz také

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)