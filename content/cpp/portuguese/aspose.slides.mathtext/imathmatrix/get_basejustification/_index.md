---
title: get_BaseJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica a justificação vertical em relação ao texto circundante. Valores possíveis são top, bottom e center. Padrão: Center"
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() método

Especifica a justificação vertical em relação ao texto circundante. Valores possíveis são top, bottom e center. Padrão: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Veja Também

* Enumeração [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)