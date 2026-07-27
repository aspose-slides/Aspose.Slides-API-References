---
title: get_Position()
second_title: Referencia de API de Aspose.Slides para C++
description: "Posición de la línea de barra. Predeterminado: Top"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() método


Posición de la línea de barra. Predeterminado: Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
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