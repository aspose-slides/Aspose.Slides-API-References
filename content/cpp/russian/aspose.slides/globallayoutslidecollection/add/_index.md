---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет новый макет слайда в презентацию.
type: docs
weight: 14
url: /ru/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) метод

Добавляет новый макет слайда в презентацию.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Слайд-шаблон для нового макета. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Имя для нового макета. Если указанное имя уже используется, будет выброшено исключение ArgumentException. Если передан параметр null, имя будет сгенерировано автоматически в соответствии с переданным типом макета (например, «Title Slide» или «1_Title Slide», «2_..», и т.д.). |

### Возвращаемое значение

Добавленный слайд.

## Примечания

1) Добавлен макет для значения [SlideLayoutType::Custom](../../slidelayouttype/) параметра *layoutType* , не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/), доступный через свойство [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## См. также

* Перечисление [SlideLayoutType](../../slidelayouttype/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [IMasterSlide](../../imasterslide/)
* Класс [String](../../../system/string/)
* Класс [GlobalLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)