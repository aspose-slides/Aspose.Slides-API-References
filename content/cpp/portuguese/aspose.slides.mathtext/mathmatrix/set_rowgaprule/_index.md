---
title: set_RowGapRule()
second_title: Referência da API Aspose.Slides para C++
description: "O tipo de espaçamento vertical entre linhas de uma matriz; as unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)"
type: docs
weight: 170
url: /pt/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) método

O tipo de espaçamento vertical entre linhas de uma matriz; As unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ver também

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)