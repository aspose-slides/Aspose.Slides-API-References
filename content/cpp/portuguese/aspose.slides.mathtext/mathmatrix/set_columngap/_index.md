---
title: set_ColumnGap()
second_title: Aspose.Slides para C++ Referência da API
description: "O valor do espaçamento horizontal entre colunas de uma matriz; se o ColumnGapRule for definido como 3 (\"Exactly\"), a unidade é interpretada como twips (1/20 de um ponto) se o ColumnGapRule for definido como 4 (\"Multiple\"), a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos, é ignorado. Padrão: 0"
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) método

O valor do espaçamento horizontal entre colunas de uma matriz; se o ColumnGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) se o ColumnGapRule for definido como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos é ignorado. Padrão: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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
* Biblioteca [Aspose.Slides](../../../)