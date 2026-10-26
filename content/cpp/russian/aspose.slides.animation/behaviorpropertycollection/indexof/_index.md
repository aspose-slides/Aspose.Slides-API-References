---
title: IndexOf()
second_title: Aspose.Slides для C++ справочник API
description: Определяет индекс конкретного элемента в IList.
type: docs
weight: 40
url: /ru/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const метод


Определяет индекс конкретного элемента в [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | Объект, который нужно найти в [IList](../../../system.collections.generic/ilist/). |

### Возвращаемое значение

Индекс *item* если найден в списке; в противном случае -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const метод


Определяет индекс конкретного элемента по значению свойства в [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | значение свойства |

### Возвращаемое значение

Индекс свойства с указанным значением

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IBehaviorProperty](../../ibehaviorproperty/)
* Класс [BehaviorPropertyCollection](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)