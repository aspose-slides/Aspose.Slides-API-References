---
title: set_ExplicitBreak()
second_title: Aspose.Slides para C++ Referência da API
description: "Explicit break especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja ajustada no início do objeto box. Especifica o número do operador na linha anterior do texto matemático que deverá ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255. Padrão: 0 (sem quebra explícita)"
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) método

Explicit break especifica se há uma quebra de linha no início do objeto Box, de modo que a linha se ajuste no início do objeto box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático valores possíveis: 1..255 Padrão: 0 (sem quebra explícita)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## Observações

Exemplo:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Veja também

* Classe [IMathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)