---
title: Contains()
second_title: Referência da API Aspose.Slides para C++
description: Determina se a coleção contém um valor específico.
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) método

Determina se a coleção contém um valor específico.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O objeto a ser localizado na coleção. |

### Valor de Retorno

verdadeiro se *item* for encontrado na coleção; caso contrário, falso.

## Observações



Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)