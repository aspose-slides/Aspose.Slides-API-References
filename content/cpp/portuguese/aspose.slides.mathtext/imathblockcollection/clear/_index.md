---
title: Clear()
second_title: Referência da API Aspose.Slides para C++
description: Remove todos os elementos da coleção.
type: docs
weight: 118
url: /pt/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() método

Remove todos os elementos da coleção.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Observações

Exemplo:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Ver também

* Classe [IMathBlockCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)