---
title: get_Position()
second_title: Referencia de API de Aspose.Slides para C++
description: "Posición del carácter de agrupación. Predeterminado: Inferior"
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() método


Posición del carácter de agrupación. Predeterminado: Inferior

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## Observaciones


Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Ver también

* Enumeración [MathTopBotPositions](../../mathtopbotpositions/)
* Clase [MathGroupingCharacter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)