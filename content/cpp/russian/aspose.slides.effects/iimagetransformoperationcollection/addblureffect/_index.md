---
title: AddBlurEffect()
second_title: Aspose.Slides для C++: справочник API
description: Добавляет новый эффект Blur в конец коллекции.
type: docs
weight: 131
url: /ru/aspose.slides.effects/iimagetransformoperationcollection/addblureffect/
---
## IImageTransformOperationCollection::AddBlurEffect(double, bool) метод

Добавляет новый эффект [Blur](../../blur/) в конец коллекции.

```cpp
virtual System::SharedPtr<IBlur> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBlurEffect(double radius, bool grow)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | **double** | Радиус размытия. |
| grow | **bool** | Указывает, должны ли границы объекта увеличиваться в результате размытия. True означает, что границы увеличены, а false — что они не увеличены. |

### Возвращаемое значение

Индекс нового эффекта изображения в коллекции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IBlur](../../iblur/)
* Класс [IImageTransformOperationCollection](../)
* Пространство имён [Aspose::Slides::Effects](../../)
* Библиотека [Aspose.Slides](../../../)