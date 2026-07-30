---
title: set_DelimiterShape()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Určuje tvar oddělovačů v objektu delimiter. Když je MathDelimiterShape::Centered, jsou oddělovače vycentrovány kolem matematické osy matematického textu a stále se přizpůsobí celé výšce jejich obsahu. Když je MathDelimiterShape::Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu."
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) metoda

Určuje tvar oddělovačů v objektu delimiter. Když je [MathDelimiterShape::Centered](../../mathdelimitershape/), jsou oddělovače centrovány kolem matematické osy matematického textu a stále se přizpůsobí celé výšce jejich obsahu. Když je [MathDelimiterShape::Match](../../mathdelimitershape/), jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
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
* Knihovna [Aspose.Slides](../../../)