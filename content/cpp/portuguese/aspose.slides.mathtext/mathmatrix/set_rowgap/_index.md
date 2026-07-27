---
title: set_RowGap()
second_title: Referência da API Aspose.Slides para C++
description: "O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 (\"Exactly\"), a unidade será interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 (\"Multiple\"), a unidade será interpretada como meio-linhas. Padrão: 0"
type: docs
weight: 196
url: /pt/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) método

O valor do espaçamento vertical entre linhas de uma matriz; Se o RowGapRule for definido como 3 ("Exactly"), a unidade será interpretada como twips (1/20 de ponto) Se o RowGapRule for definido como 4 ("Multiple"), a unidade será interpretada como meio-linhas. Padrão: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Veja também

* Classe [MathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)