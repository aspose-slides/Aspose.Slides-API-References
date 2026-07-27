---
title: get_DelimiterShape()
second_title: Referência da API Aspose.Slides for C++
description: "Especifica a forma dos delimitadores no objeto delimitador. Quando é MathDelimiterShape::Centered, os delimitadores são centralizados ao redor do eixo matemático do texto matemático e ainda são ajustados para caber na altura total de seus conteúdos. Quando é MathDelimiterShape::Match, sua altura e forma são alteradas para corresponder exatamente aos seus conteúdos."
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() método

Especifica a forma dos delimitadores no objeto delimitador. Quando é [MathDelimiterShape::Centered](../../mathdelimitershape/), os delimitadores são centralizados ao redor do eixo matemático do texto matemático e ainda são ajustados para caber na altura total de seu conteúdo. Quando é [MathDelimiterShape::Match](../../mathdelimitershape/), sua altura e forma são alteradas para corresponder exatamente ao seu conteúdo.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Observações

Exemplo:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Veja Também

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)