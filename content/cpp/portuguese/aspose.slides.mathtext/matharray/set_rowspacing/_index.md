---
title: set_RowSpacing()
second_title: Aspose.Slides para C++ Referência da API
description: "Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos ou Multiple, nesse caso a unidade de medida é meio-linhas. Padrão: 0"
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) método

Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos ou Multiple, nesse caso a unidade de medida é meio-linhas. Padrão: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Observações


Exemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Ver também

* Classe [MathArray](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)