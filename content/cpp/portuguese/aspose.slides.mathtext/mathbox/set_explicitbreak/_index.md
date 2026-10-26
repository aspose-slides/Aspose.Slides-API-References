---
title: set_ExplicitBreak()
second_title: Referência da API Aspose.Slides para C++
description: "Explicit break especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255 Padrão: 0 (nenhuma quebra explícita)"
type: docs
weight: 131
url: /pt/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) método

Explicit break especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255 Padrão: 0 (nenhuma quebra explícita)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Observações

Exemplo:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Ver também

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)