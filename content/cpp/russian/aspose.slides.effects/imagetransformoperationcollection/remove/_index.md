---
title: Remove()
second_title: Aspose.Slides для C++ Справочник API
description: Удаляет первое вхождение конкретного объекта из ICollection.
type: docs
weight: 339
url: /ru/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) метод

Удаляет первое вхождение конкретного объекта из [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | Объект, который необходимо удалить из [ICollection](../../../system.collections.generic/icollection/). |

### Возвращаемое значение

true, если *item* был успешно удалён из [ICollection](../../../system.collections.generic/icollection/); в противном случае — false. Этот метод также возвращает false, если *item* не найден в исходном [ICollection](../../../system.collections.generic/icollection/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IImageTransformOperation](../../iimagetransformoperation/)
* Класс [ImageTransformOperationCollection](../)
* Пространство имён [Aspose::Slides::Effects](../../)
* Библиотека [Aspose.Slides](../../../)