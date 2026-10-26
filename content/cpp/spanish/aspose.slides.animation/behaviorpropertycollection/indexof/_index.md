---
title: IndexOf()
second_title: Aspose.Slides para C++ Referencia de API
description: Determina el índice de un elemento específico en el IList.
type: docs
weight: 40
url: /es/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method


Determina el índice de un elemento específico en el [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | El objeto a localizar en el [IList](../../../system.collections.generic/ilist/). |

### Valor de retorno

El índice de *item* si se encuentra en la lista; de lo contrario, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method


Determina el índice de un elemento específico por valor de propiedad en el [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | valor de la propiedad |

### Valor de retorno

El índice de la propiedad con el valor especificado

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBehaviorProperty](../../ibehaviorproperty/)
* Clase [BehaviorPropertyCollection](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)