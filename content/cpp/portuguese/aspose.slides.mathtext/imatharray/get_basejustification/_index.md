---
title: get_BaseJustification()
second_title: Aspose.Slides para C++ Referência da API
description: "Especifica o alinhamento da matriz em relação ao texto circundante. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou central de um objeto de matriz. Valor padrão: Center"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() método

Especifica o alinhamento da matriz em relação ao texto ao redor. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou central de um objeto de matriz. Valor padrão: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Observações

Exemplo:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ver Também

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)