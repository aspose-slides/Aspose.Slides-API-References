---
title: get_ExplicitBreak()
second_title: Referência da API Aspose.Slides para C++
description: "A quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático valores possíveis: 1..255 Padrão: 0 (sem quebra explícita)"
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() método

A quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. Especifica o número do operador na linha anterior do texto matemático que deverá ser usado como ponto de alinhamento para a linha atual do texto matemático valores possíveis: 1..255 Padrão: 0 (sem quebra explícita)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Observações

Exemplo:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Ver também

* Classe [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)