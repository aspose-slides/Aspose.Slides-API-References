---
title: get_Position()
second_title: Referência da API Aspose.Slides for C++
description: "Posição da linha da barra. Padrão: Top"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() método


Posição da linha da barra. Padrão: Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## Observações


Exemplo: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Veja Também

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Classe [MathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)