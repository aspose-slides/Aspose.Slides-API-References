---
title: Add()
second_title: Aspose.Slides для C++ API Справка
description: Добавляет новый макетный слайд в презентацию.
type: docs
weight: 14
url: /ru/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

Добавляет новый макетный слайд в презентацию.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Слайд-мастер для нового макета. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException. Если передан параметр null, имя генерируется автоматически в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Возвращаемое значение

Добавленный слайд.

## Примечания

1) Добавленный макет для значения [SlideLayoutType::Custom](../../slidelayouttype/) параметра *layoutType* не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/), доступный через свойство [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## См. также

* Перечисление [SlideLayoutType](../../slidelayouttype/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [IMasterSlide](../../imasterslide/)
* Класс [String](../../../system/string/)
* Класс [IGlobalLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)