---
title: get_Position()
second_title: Referencia de API de Aspose.Slides para C++
description: "Posición de la línea de barra. Predeterminado: Top"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() método


Posición de la línea de barra. Predeterminado: Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## Observaciones


Ejemplo: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Clase [MathBar](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)