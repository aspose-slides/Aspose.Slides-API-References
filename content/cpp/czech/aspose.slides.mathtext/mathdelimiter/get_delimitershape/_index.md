---
title: get_DelimiterShape()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Určuje tvar oddělovačů v objektu delimiter. Když je MathDelimiterShape::Centered, jsou oddělovače vycentrovány kolem matematické osy matematického textu a jsou přizpůsobeny tak, aby odpovídaly celé výšce jejich obsahu. Když je MathDelimiterShape::Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu."
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metoda


Určuje tvar oddělovačů v objektu delimiter. Když je [MathDelimiterShape::Centered](../../mathdelimitershape/), jsou oddělovače vycentrovány kolem matematické osy matematického textu a stále jsou přizpůsobeny tak, aby odpovídaly celé výšce jejich obsahu. Když je [MathDelimiterShape::Match](../../mathdelimitershape/), jsou jejich výška a tvar upraveny tak, aby přesně odpovídaly jejich obsahu.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Viz také

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)