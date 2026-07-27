---
title: get_RowSpacing()
second_title: Referência da API Aspose.Slides para C++
description: "Espaçamento entre linhas de uma matriz. É usado somente quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos ou Multiple, nesse caso a unidade de medida é meia linha. Padrão: 0"
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() method

Espaçamento entre linhas de uma matriz É usado apenas quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos ou Multiple, nesse caso a unidade de medida é meia linha. Padrão: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
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