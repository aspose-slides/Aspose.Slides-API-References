---
title: AddBlurEffect()
second_title: Aspose.Slides для C++ API Reference
description: Добавляет новый эффект размытия в конец коллекции.
type: docs
weight: 157
url: /ru/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) метод


Добавляет новый эффект [Blur](../../blur/) в конец коллекции.

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | **double** | Радиус размытия. |
| grow | **bool** | Указывает, следует ли увеличить границы объекта в результате размытия. True указывает, что границы увеличены, а false — что они не увеличены. |

### Возвращаемое значение

Индекс нового эффекта изображения в коллекции.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBlur](../../iblur/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)