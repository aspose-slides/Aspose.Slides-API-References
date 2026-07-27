---
title: get_DelimiterShape()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica a forma dos delimitadores no objeto delimitador. Quando é MathDelimiterShape::Centered, os delimitadores são centralizados em torno do eixo matemático do texto matemático e ainda são ajustados para caber na altura total de seus conteúdos. Quando é MathDelimiterShape::Match, sua altura e forma são alteradas para corresponder exatamente aos seus conteúdos."
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() método

Especifica a forma dos delimitadores no objeto delimitador. Quando é [MathDelimiterShape::Centered](../../mathdelimitershape/), os delimitadores são centralizados em torno do eixo matemático do texto matemático e ainda são feitos para caber na altura total de seus conteúdos. Quando é [MathDelimiterShape::Match](../../mathdelimitershape/), sua altura e forma são alteradas para corresponder exatamente aos seus conteúdos.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Ver Também

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [IMathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)