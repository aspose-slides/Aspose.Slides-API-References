---
title: Remove()
second_title: Referência de API Aspose.Slides para C++
description: Remove a primeira ocorrência de um objeto específico da coleção/>.
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) método


Remove a primeira ocorrência de um objeto específico da coleção/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | O objeto a ser removido da coleção. |

### Valor de Retorno

true se *item* foi removido com sucesso da coleção; caso contrário, false. Este método também retorna false se *item* não for encontrado na coleção original/>.

## Observações



Exemplo: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)