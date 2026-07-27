---
title: get_Count()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de elementos realmente contidos na coleção. Somente leitura int32_t.
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() método


Obtém o número de elementos realmente contidos na coleção. Somente leitura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Observações


Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Veja Também

* Classe [IMathBlockCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)