---
title: get_RowSpacing()
second_title: Referência da API Aspose.Slides para C++
description: "Espaçamento entre linhas de um array. É usado apenas quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos ou Multiple, caso em que a unidade de medida é meia linha. Padrão: 0"
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() método


Espaçamento entre linhas de um array É usado apenas quando RowSpacingRule está definido como 3 Exatamente, caso em que a unidade de medida é pontos ou Multiple, caso em que a unidade de medida é meia linha. Padrão: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Observações


Exemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Ver também

* Classe [IMathArray](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)