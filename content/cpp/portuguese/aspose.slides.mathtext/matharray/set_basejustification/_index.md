---
title: set_BaseJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o alinhamento da matriz em relação ao texto ao redor. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou central de um objeto matriz. Valor padrão: Center"
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) método

Especifica o alinhamento da matriz em relação ao texto ao redor. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou central de um objeto matriz. Valor padrão: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
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