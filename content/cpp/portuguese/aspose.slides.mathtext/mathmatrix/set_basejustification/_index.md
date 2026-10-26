---
title: set_BaseJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica a justificação vertical em relação ao texto ao redor. Os valores possíveis são superior, inferior e central. Padrão: Central"
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) método


Especifica a justificação vertical em relação ao texto ao redor. Os valores possíveis são superior, inferior e central. Padrão: Central

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
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