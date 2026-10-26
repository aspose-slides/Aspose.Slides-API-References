---
title: CopyTo()
second_title: Aspose.Slides для C++ справочника API
description: "Копирует элементы ICollection в System::Array, начиная с определённого индекса System::Array."
type: docs
weight: 66
url: /ru/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) метод

Копирует элементы [ICollection](../../../system.collections.generic/icollection/) в [System::Array](../../../system/array/), начиная с определённого индекса [System::Array](../../../system/array/).

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | Одномерный [System::Array](../../../system/array/), являющийся получателем элементов, скопированных из [ICollection](../../../system.collections.generic/icollection/). [System::Array](../../../system/array/) должен иметь нулевую индексацию. |
| arrayIndex | **int32_t** | Нулевой индекс в *array*, с которого начинается копирование. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IBehaviorProperty](../../ibehaviorproperty/)
* Класс [BehaviorPropertyCollection](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)