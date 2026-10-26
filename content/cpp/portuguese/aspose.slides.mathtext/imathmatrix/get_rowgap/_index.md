---
title: get_RowGap()
second_title: Referência da API Aspose.Slides para C++
description: "O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 (\"Exactly\"), então a unidade é interpretada como twips (1/20 de um ponto) Se o RowGapRule for definido como 4 (\"Multiple\"), então a unidade é interpretada como meia-linha. Padrão: 0"
type: docs
weight: 183
url: /pt/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() método


O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), então a unidade é interpretada como twips (1/20 de um ponto) Se o RowGapRule for definido como 4 ("Multiple"), então a unidade é interpretada como meia-linha. Padrão: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Observações


Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Veja Também

* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)