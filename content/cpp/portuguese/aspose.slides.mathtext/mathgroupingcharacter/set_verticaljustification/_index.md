---
title: set_VerticalJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base. Padrão: Bottom para Position=Top e Top para Position=Bottom"
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) método

Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base. Padrão: Bottom para Position=Top, e Top para Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Observações

Exemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Veja Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)