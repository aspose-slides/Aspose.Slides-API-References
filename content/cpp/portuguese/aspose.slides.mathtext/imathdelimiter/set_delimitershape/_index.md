---
title: set_DelimiterShape()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica a forma dos delimitadores no objeto delimitador. Quando é MathDelimiterShape::Centered, os delimitadores são centralizados em torno do eixo matemático do texto matemático e ainda são ajustados para ocupar toda a altura de seu conteúdo. Quando é MathDelimiterShape::Match, sua altura e forma são alteradas para corresponder exatamente ao seu conteúdo."
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) método

Especifica a forma dos delimitadores no objeto delimitador. Quando é [MathDelimiterShape::Centered](../../mathdelimitershape/), os delimitadores são centralizados em torno do eixo matemático do texto matemático e ainda são ajustados para ocupar toda a altura de seu conteúdo. Quando é [MathDelimiterShape::Match](../../mathdelimitershape/), sua altura e forma são alteradas para corresponder exatamente ao seu conteúdo.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Veja Também

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)