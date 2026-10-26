---
title: set_ColumnGapRule()
second_title: Referência da API Aspose.Slides para C++
description: "O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)"
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) método

O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Veja Também

* Enum [MathSpacingRules](../../mathspacingrules/)
* classe [MathMatrix](../)
* espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)