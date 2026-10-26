---
title: get_Count()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de elementos matemáticos filhos realmente contidos na coleção. Somente leitura int32_t.
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() método

Obtém o número de elementos matemáticos filhos realmente contidos na coleção. Somente leitura **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Observações

Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## Veja Também

* Classe [MathBlock](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)