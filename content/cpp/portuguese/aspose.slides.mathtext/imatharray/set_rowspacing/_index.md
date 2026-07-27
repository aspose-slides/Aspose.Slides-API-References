---
title: set_RowSpacing()
second_title: Referência da API Aspose.Slides para C++
description: "Espaçamento entre linhas de uma matriz. É usado somente quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos ou Multiple, nesse caso a unidade de medida é meias linhas. Padrão: 0"
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) método

Espaçamento entre linhas de uma matriz. É usado somente quando RowSpacingRule está definido como 3, exatamente nesse caso a unidade de medida é pontos, ou Multiple, nesse caso a unidade de medida é meias linhas. Padrão: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Observações

Exemplo:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Veja também

* Classe [IMathArray](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)