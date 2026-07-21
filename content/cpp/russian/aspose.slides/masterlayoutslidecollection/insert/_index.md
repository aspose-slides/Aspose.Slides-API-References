---
title: Insert()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет новый слайд-макет в указанную позицию коллекции.
type: docs
weight: 40
url: /ru/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method


Вставляет новый слайд-макет в указанную позицию коллекции.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Имя нового макета. Если переданное имя уже используется, будет выброшено ArgumentException. Если передан null, имя генерируется автоматически в зависимости от переданного типа макета (например, \"Title Slide\" или \"1_Title Slide\", \"2_..\", и т.д.). |

### Return Value

Вставленный слайд.

## Remarks

Вставленный макет для значения [SlideLayoutType::Custom](../../slidelayouttype/) параметра *layoutType* не содержит заполнителей и фигур.

## See Also

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)