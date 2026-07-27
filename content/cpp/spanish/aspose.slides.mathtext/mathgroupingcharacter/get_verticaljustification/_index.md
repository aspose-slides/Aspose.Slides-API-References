---
title: get_VerticalJustification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está por encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se sitúa en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base Predeterminado: Bottom para Position=Top, y Top para Position=Bottom"
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() método

Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está por encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se encuentra en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base Predeterminado: Bottom para Position=Top, y Top para Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Observaciones

Ejemplo:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Ver también

* Enumeración [MathTopBotPositions](../../mathtopbotpositions/)
* Clase [MathGroupingCharacter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)