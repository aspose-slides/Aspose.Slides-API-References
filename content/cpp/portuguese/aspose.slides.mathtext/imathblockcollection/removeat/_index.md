---
title: RemoveAt()
second_title: Referência da API Aspose.Slides for C++
description: Remove um item no índice especificado da coleção.
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) método

Remove um item no índice especificado da coleção.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero do item a ser removido. |
## Observações



Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Ver também

* Classe [IMathBlockCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)