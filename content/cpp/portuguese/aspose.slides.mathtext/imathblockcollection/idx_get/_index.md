---
title: idx_get()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o item no índice especificado. Somente leitura IMathBlock.
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) método

Obtém o item no índice especificado. Somente leitura [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero do item a ser obtido |

### Valor de Retorno

O bloco de um texto matemático.
## Observações



Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)