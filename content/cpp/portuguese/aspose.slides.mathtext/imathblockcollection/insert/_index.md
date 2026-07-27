---
title: Insert()
second_title: Referência da API Aspose.Slides para C++
description: Insere IMathBlock na coleção no índice especificado.
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) método

Insere [IMathBlock](../../imathblock/) na coleção no índice especificado.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual um item deve ser inserido. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O [IMathBlock](../../imathblock/) a ser inserido. |
## Observações



Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)