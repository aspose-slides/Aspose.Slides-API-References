---
title: get_BaseJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica a justificação vertical em relação ao texto ao redor. Valores possíveis são top, bottom e center. Padrão: Center"
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() método

Especifica a justificação vertical em relação ao texto ao redor. Os valores possíveis são top, bottom e center. Padrão: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Ver também

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)