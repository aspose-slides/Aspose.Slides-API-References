---
title: get_ColumnGap()
second_title: Aspose.Slides para C++ Referência da API
description: "O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 (\"Exactly\"), então a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 (\"Multiple\"), então a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos, ignorado. Padrão: 0"
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() método


O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 ("Exactly"), então a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 ("Multiple"), então a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos, ignorado. Padrão: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Observações


Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Veja Também

* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)