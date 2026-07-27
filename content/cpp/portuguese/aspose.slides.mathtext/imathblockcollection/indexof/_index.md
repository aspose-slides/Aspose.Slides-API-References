---
title: IndexOf()
second_title: Aspose.Slides para C++ Referência da API
description: Determina o índice de um IMathBlock específico na coleção.
type: docs
weight: 79
url: /pt/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) método

Determina o índice de um [IMathBlock](../../imathblock/) específico na coleção.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O item a ser localizado na coleção. |

### Valor de Retorno

O índice de *item* se encontrado na coleção; caso contrário, -1.

## Observações

Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)