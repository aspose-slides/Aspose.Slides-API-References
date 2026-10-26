---
title: Remove()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет макет из коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) метод

Удаляет макет из коллекции.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Слайд макета, который следует удалить из коллекции. |

## Примечания

1) Чтобы избежать выбрасывания PptxEditException, проверьте свойство HasDependingSlides макета ранее. 2) Вы также можете использовать метод [ILayoutSlide::Remove](../../ilayoutslide/remove/), чтобы упростить код. 

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [ILayoutSlideCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)