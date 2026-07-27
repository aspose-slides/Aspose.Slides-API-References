---
title: IndexOf()
second_title: Referência da API Aspose.Slides for C++
description: Determina o índice de um item específico na IList.
type: docs
weight: 40
url: /pt/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method

Determina o índice de um item específico em [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | O objeto a ser localizado em [IList](../../../system.collections.generic/ilist/). |

### Valor de Retorno

O índice de *item* se encontrado na lista; caso contrário, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method

Determina o índice de um item específico pelo valor da propriedade em [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | valor da propriedade |

### Valor de Retorno

O índice da propriedade com o valor especificado

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBehaviorProperty](../../ibehaviorproperty/)
* Classe [BehaviorPropertyCollection](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Biblioteca [Aspose.Slides](../../../)