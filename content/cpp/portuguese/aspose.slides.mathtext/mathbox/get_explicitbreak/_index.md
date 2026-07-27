---
title: get_ExplicitBreak()
second_title: Referência da API Aspose.Slides para C++
description: "O explicit break especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja envolvida no início do objeto box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255. Padrão: 0 (nenhuma quebra explícita)."
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() método


O explicit break especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja envolvida no início do objeto box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255 Padrão: 0 (nenhuma quebra explícita)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Observações


Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Veja também

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)