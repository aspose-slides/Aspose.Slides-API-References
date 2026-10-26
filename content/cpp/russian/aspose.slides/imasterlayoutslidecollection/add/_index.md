---
title: Add()
second_title: Aspose.Slides для C++ справка по API
description: Добавляет новый макетный слайд в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) метод


Добавляет новый слайд макета в конец коллекции.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в данный момент не поддерживаются: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Имя для нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан параметр null, имя генерируется автоматически в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Возвращаемое значение

Добавленный слайд.

## Примечания

1) Добавлен макет для значения [SlideLayoutType::Custom](../../slidelayouttype/) параметра *layoutType*, не содержит заполнителей и фигур. 2) Аналог этого метода — метод [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/), доступный через свойство [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## См. также

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [String](../../../system/string/)
* Класс [IMasterLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)