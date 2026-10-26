---
title: set_VerticalJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Justificação vertical do caractere de agrupamento. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de agrupamento está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está sobre a linha de base; quando VerticalJustification é definido como Bottom, a parte inferior do objeto está sobre a linha de base Default: Bottom for Position=Top, and Top for Position=Bottom"
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) method

Justificação vertical do caractere de agrupamento. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de agrupamento está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está sobre a linha de base; quando VerticalJustification é definido como Bottom, a parte inferior do objeto está sobre a linha de base. Default: Bottom for Position=Top, and Top for Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Observações

Exemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Ver Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)