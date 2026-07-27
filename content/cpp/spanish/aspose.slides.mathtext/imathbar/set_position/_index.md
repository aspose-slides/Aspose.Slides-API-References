---
title: set_Position()
second_title: Referencia de API de Aspose.Slides para C++
description: "Posición de la línea de barra. Predeterminado: Top"
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathbar/set_position/
---
## IMathBar::set_Position(MathTopBotPositions) método


Posición de la línea de barra. Predeterminado: Top

```cpp
virtual void Aspose::Slides::MathText::IMathBar::set_Position(MathTopBotPositions value)=0
```

## Observaciones


Ejemplo:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Ver también

* Enumeración [MathTopBotPositions](../../mathtopbotpositions/)
* Clase [IMathBar](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)