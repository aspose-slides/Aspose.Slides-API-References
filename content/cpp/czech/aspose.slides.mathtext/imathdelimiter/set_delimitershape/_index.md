---
title: set_DelimiterShape()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje tvar omezovačů v objektu omezovače. Když je MathDelimiterShape::Centered, omezovače jsou vycentrovány kolem matematické osy matematického textu a stále se přizpůsobují celé výšce jejich obsahu. Když je MathDelimiterShape::Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu."
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) metoda


Specifikuje tvar omezovačů v objektu omezovače. Když je [MathDelimiterShape::Centered](../../mathdelimitershape/), omezovače jsou vycentrovány kolem matematické osy matematického textu a stále se přizpůsobují celé výšce jejich obsahu. Když je [MathDelimiterShape::Match](../../mathdelimitershape/), jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Poznámky


Příklad:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Viz také

* Výčet [MathDelimiterShape](../../mathdelimitershape/)
* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)