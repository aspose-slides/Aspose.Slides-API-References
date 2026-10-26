---
title: get_RowGap()
second_title: Aspose.Slides para C++ Referência da API
description: "O valor do espaçamento vertical entre linhas de uma matriz; Se RowGapRule for definido como 3 (\"Exactly\"), então a unidade é interpretada como twips (1/20 de um ponto) Se RowGapRule for definido como 4 (\"Multiple\"), então a unidade é interpretada como meias linhas. Padrão: 0"
type: docs
weight: 183
url: /pt/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() método

O valor do espaçamento vertical entre linhas de uma matriz; Se RowGapRule estiver definido como 3 ("Exactly"), então a unidade é interpretada como twips (1/20 de um ponto) Se RowGapRule estiver definido como 4 ("Multiple"), então a unidade é interpretada como meia-linha. Padrão: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Ver também

* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)