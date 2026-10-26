---
title: get_ColumnGapRule()
second_title: Referência da API Aspose.Slides para C++
description: "O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)"
type: docs
weight: 105
url: /pt/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() método


O tipo de espaçamento horizontal entre colunas de uma matriz; as unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Observações


Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ver também

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)