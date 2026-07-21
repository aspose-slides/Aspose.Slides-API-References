---
title: AddBiLevelEffect()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет новый Bi-Level (чёрно-белый) эффект в конец коллекции.
type: docs
weight: 118
url: /ru/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(float) метод


Добавляет новый Bi-Level (чёрно-белый) эффект в конец коллекции.

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | **float** | порог яркости для эффекта Bi-Level. Значения, большие или равные порогу, устанавливаются в белый. Значения, меньшие порога, устанавливаются в чёрный. |

### Возвращаемое значение

Индекс нового эффекта изображения в коллекции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBiLevel](../../ibilevel/)
* Class [IImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)