---
title: Add()
second_title: Aspose.Slides для C++ справка по API
description: Добавляет новый слайд макета в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) метод

Добавляет новый слайд макета в конец коллекции.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Тип разметки для нового макета. Поддерживаемые типы разметки: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы разметки в настоящее время не поддерживаются: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException. Если передан параметр null, имя генерируется автоматически в зависимости от переданного типа макета (например "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Return Value

Добавленный слайд.

## Remarks

1) Добавленный макет для значения [SlideLayoutType::Custom](../../slidelayouttype/) параметра *layoutType* не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/), доступный через свойство [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## See Also

* Перечисление [SlideLayoutType](../../slidelayouttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [String](../../../system/string/)
* Класс [MasterLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)