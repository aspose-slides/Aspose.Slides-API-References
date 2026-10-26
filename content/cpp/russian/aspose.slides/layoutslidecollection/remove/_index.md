---
title: Remove()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет макет из коллекции.
type: docs
weight: 66
url: /ru/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) метод

Удаляет макет из коллекции.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Макет слайда, который нужно удалить из коллекции. |
## Примечания

1) Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides макета заранее. 2) Вы также можете использовать метод [ILayoutSlide::Remove](../../ilayoutslide/remove/) для упрощения кода. 
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [LayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)