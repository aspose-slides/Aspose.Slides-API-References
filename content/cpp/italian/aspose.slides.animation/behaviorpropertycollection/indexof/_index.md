---
title: IndexOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina l'indice di un elemento specifico nella IList.
type: docs
weight: 40
url: /it/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const metodo

Determina l'indice di un elemento specifico nella [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | L'oggetto da individuare nella [IList](../../../system.collections.generic/ilist/). |

### Valore di ritorno

L'indice di *item* se trovato nell'elenco; altrimenti, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const metodo

Determina l'indice di un elemento specifico per valore di proprietà nella [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | valore della proprietà |

### Valore di ritorno

L'indice della proprietà con il valore specificato

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBehaviorProperty](../../ibehaviorproperty/)
* Classe [BehaviorPropertyCollection](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)