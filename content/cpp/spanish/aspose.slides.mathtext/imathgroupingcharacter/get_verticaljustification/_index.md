---
title: get_VerticalJustification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea de base. Por ejemplo, cuando el carácter de grupo está encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se sitúa en la línea de base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea de base Predeterminado: Bottom para Position=Top, y Top para Position=Bottom"
type: docs
weight: 66
url: /es/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() método

Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se sitúa en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top, y Top para Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Observaciones

Ejemplo:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)