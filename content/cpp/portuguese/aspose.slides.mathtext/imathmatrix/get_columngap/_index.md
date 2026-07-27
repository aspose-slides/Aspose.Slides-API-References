---
title: get_ColumnGap()
second_title: Referência da API Aspose.Slides para C++
description: "O valor do espaçamento horizontal entre as colunas de uma matriz; Se o ColumnGapRule for definido como 3 (\"Exactly\"), então a unidade é interpretada como twips (1/20 de um ponto) Se o ColumnGapRule for definido como 4 (\"Multiple\"), então a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos, ignorado. Default: 0"
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() método


O valor do espaçamento horizontal entre as colunas de uma matriz; Se o ColumnGapRule for definido como 3 (\"Exactly\"), então a unidade é interpretada como twips (1/20 de um ponto) Se o ColumnGapRule for definido como 4 (\"Multiple\"), então a unidade é interpretada como número de incrementos de 0.5 em. Em outros casos, ignorado. Default: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Observações


Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Veja também

* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)