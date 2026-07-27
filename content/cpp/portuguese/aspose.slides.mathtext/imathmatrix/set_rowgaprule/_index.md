---
title: set_RowGapRule()
second_title: Referência da API Aspose.Slides para C++
description: "O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)"
type: docs
weight: 170
url: /pt/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) método

O tipo de espaçamento vertical entre linhas de uma matriz; As unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
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
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)