---
title: Insert()
second_title: Aspose.Slides для C++ справочник API
description: Вставляет новый макетный слайд в указанную позицию коллекции.
type: docs
weight: 40
url: /ru/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) метод


Вставляет новый макетный слайд в указанную позицию коллекции.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов сейчас не поддерживаются: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException. Если передан параметр null, имя будет сгенерировано автоматически в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Возвращаемое значение

Вставленный слайд.

## Примечание

Вставленный макет для значения [SlideLayoutType::Custom](../../slidelayouttype/) типа *layoutType* не содержит заполнителей и фигур. 

## См. также

* Перечисление [SlideLayoutType](../../slidelayouttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [String](../../../system/string/)
* Класс [IMasterLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)