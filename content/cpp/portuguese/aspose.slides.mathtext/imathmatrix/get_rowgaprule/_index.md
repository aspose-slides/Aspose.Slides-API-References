---
title: get_RowGapRule()
second_title: Referência da API Aspose.Slides para C++
description: "O tipo de espaçamento vertical entre as linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)"
type: docs
weight: 157
url: /pt/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() método


O tipo de espaçamento vertical entre as linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Observações


Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Veja Também

* Enumeração [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)