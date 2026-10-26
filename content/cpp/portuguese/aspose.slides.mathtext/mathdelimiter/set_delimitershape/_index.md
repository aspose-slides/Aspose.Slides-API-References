---
title: set_DelimiterShape()
second_title: Referência da API Aspose.Slides for C++
description: "Especifica a forma dos delimitadores no objeto delimitador. Quando é MathDelimiterShape::Centered, os delimitadores são centralizados em torno do eixo matemático do texto matemático e ainda são ajustados para caber na altura total de seu conteúdo. Quando é MathDelimiterShape::Match, sua altura e forma são alteradas para coincidir exatamente com seu conteúdo."
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) método

Especifica a forma dos delimitadores no objeto delimitador. Quando é [MathDelimiterShape::Centered](../../mathdelimitershape/), os delimitadores são centralizados em torno do eixo matemático do texto matemático e ainda são ajustados para caber na altura total de seu conteúdo. Quando é [MathDelimiterShape::Match](../../mathdelimitershape/), sua altura e forma são alteradas para coincidir exatamente com seu conteúdo.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Veja também

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)