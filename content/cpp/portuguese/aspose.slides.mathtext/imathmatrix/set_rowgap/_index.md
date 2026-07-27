---
title: set_RowGap()
second_title: Referência da API Aspose.Slides para C++
description: "O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 (\"Exactly\"), a unidade é interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 (\"Multiple\"), a unidade é interpretada como meia-linha. Padrão: 0"
type: docs
weight: 196
url: /pt/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) método

O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 ("Multiple"), a unidade é interpretada como meia-linha. Padrão: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)