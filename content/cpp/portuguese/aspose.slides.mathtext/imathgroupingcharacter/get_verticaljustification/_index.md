---
title: get_VerticalJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto fica na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base Padrão: Bottom para Position=Top, e Top para Position=Bottom"
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() método

Justificação vertical do caractere de grupo. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de grupo está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto fica na linha de base; quando VerticalJustification está definido como Bottom, a parte inferior do objeto está na linha de base Padrão: Bottom para Position=Top, e Top para Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Observações

Exemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Ver também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)