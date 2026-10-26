---
title: get_BaseJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o alinhamento da matriz em relação ao texto circundante. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou ao centro de um objeto matriz. Valor padrão: Center"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() método


Especifica o alinhamento da matriz em relação ao texto ao redor. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou ao centro de um objeto matriz. Valor padrão: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Observações


Exemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ver também

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)