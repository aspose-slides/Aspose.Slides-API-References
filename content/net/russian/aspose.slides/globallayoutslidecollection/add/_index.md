---
title: Add
second_title: Aspose.Sildes для .NET API справочник
description: Добавляет новый макетный слайд в презентацию.
type: docs
weight: 10
url: /ru/aspose.slides/globallayoutslidecollection/add/
---

## GlobalLayoutSlideCollection.Add метод

Добавляет новый макетный слайд в презентацию.

```csharp
public ILayoutSlide Add(IMasterSlide master, SlideLayoutType layoutType, string layoutName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| master | IMasterSlide | Мастер-слайд для нового макета. |
| layoutType | SlideLayoutType | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Имя для нового макета. Если переданное имя уже используется, будет вызвано исключение ArgumentException. Если передан параметр null, то имя будет сгенерировано автоматически в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_..", и так далее). |

### Возвращаемое значение

Добавленный слайд.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | Выбрасывается, если передано неподдерживаемое значение параметра *layoutType*. Типы макетов, которые сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| ArgumentNullException | Выбрасывается, если *master* равно null. |
| ArgumentException | Выбрасывается, если *master* принадлежит другой презентации. |
| ArgumentException | Выбрасывается, если значение имени макета *layoutName* уже используется в коллекции макетов *master*. |

### Замечания

1) Добавленный макет для значения SlideLayoutType.Custom из *layoutType* не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [`Add`](../../imasterlayoutslidecollection/add), доступный через свойство [`LayoutSlides`](../../imasterslide/layoutslides).

### См. также

* интерфейс [ILayoutSlide](../../ilayoutslide)
* интерфейс [IMasterSlide](../../imasterslide)
* перечисление [SlideLayoutType](../../slidelayouttype)
* класс [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* пространство имен [Aspose.Slides](../../globallayoutslidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->