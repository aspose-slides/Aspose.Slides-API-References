---
title: AddBiLevelEffect()
second_title: Справка по API Aspose.Slides для C++
description: Добавляет новый биуровневый (чёрно-белый) эффект в конец коллекции.
type: docs
weight: 144
url: /ru/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) метод


Добавляет новый биуровневый (чёрно-белый) эффект в конец коллекции.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| threshold | **float** | пороговая яркость для биуровневого эффекта. Значения, большие или равные порогу, устанавливаются в белый. Значения, меньшие порога, устанавливаются в чёрный. |

### Возвращаемое значение

Индекс нового ефекта изображения в коллекции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBiLevel](../../ibilevel/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)