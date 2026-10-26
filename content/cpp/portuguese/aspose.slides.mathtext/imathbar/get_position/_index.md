---
title: get_Position()
second_title: Referência da API Aspose.Slides para C++
description: "Posição da linha da barra. Padrão: Top"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() método

Posição da linha da barra. Padrão: Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Observações

Exemplo:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Ver também

* Enumeração [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [IMathBar](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)