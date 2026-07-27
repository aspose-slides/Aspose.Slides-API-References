---
title: set_ColumnGapRule()
second_title: Aspose.Slides para C++ Referência da API
description: "O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)"
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) método

O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ver Também

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)