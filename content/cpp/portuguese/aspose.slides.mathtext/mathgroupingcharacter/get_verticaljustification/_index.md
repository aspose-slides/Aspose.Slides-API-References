---
title: get_VerticalJustification()
second_title: Aspose.Slides para C++ Referência da API
description: "Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto fica na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base Padrão: Bottom para Position=Top, e Top para Position=Bottom"
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() método

Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto fica na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base Padrão: Bottom para Position=Top, e Top para Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Observações

Exemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Veja também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)