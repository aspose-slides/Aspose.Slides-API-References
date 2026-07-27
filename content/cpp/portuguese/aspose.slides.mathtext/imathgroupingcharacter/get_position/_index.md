---
title: get_Position()
second_title: Aspose.Slides para C++ Referência da API
description: "Posição do caractere de agrupamento. Padrão: Inferior"
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() método

Posição do caractere de agrupamento. Padrão: Inferior

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Observações

Exemplo:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Ver também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)