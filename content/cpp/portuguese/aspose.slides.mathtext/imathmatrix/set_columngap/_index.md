---
title: set_ColumnGap()
second_title: Referência da API Aspose.Slides for C++
description: "O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 (\"Exactly\"), então a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 (\"Multiple\"), então a unidade é interpretada como número de incrementos de 0.5 em. Em outros casos, ignorado. Default: 0"
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) método

O valor do espaçamento horizontal entre colunas de uma matriz; Se o ColumnGapRule for definido como 3 ("Exactly"), então a unidade é interpretada como twips (1/20 de ponto) Se o ColumnGapRule for definido como 4 ("Multiple"), então a unidade é interpretada como número de incrementos de 0.5 em. Em outros casos, ignorado. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Ver também

* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)