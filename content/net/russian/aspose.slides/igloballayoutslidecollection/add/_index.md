---
title: Add
second_title: Справочник по API Aspose.Slides для .NET
description: Добавляет новый слайд макета в презентацию.
type: docs
weight: 20
url: /ru/aspose.slides/igloballayoutslidecollection/add/
---

## Метод IGlobalLayoutSlideCollection.Add

Добавляет новый слайд макета в презентацию.

```csharp
public ILayoutSlide Add(IMasterSlide master, SlideLayoutType layoutType, string layoutName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| master | IMasterSlide | Основной слайд для нового макета. |
| layoutType | SlideLayoutType | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Имя для нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан параметр null, будет автоматически сгенерировано имя в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_..", и т.д.). |

### Возвращаемое значение

Добавленный слайд.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | Выбрасывается, если передано неподдерживаемое значение параметра *layoutType*. Типы макетов, которые сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| ArgumentNullException | Выбрасывается, если *master* равно null. |
| ArgumentException | Выбрасывается, если *master* принадлежит другой презентации. |
| ArgumentException | Выбрасывается, если значение имени макета *layoutName* уже используется в коллекции макетов *master*. |

### Примечания

1) Добавленный макет для значения SlideLayoutType.Custom из *layoutType* не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [`Add`](../../imasterlayoutslidecollection/add), доступный через свойство [`LayoutSlides`](../../imasterslide/layoutslides).

### См. также

* интерфейс [ILayoutSlide](../../ilayoutslide)
* интерфейс [IMasterSlide](../../imasterslide)
* перечисление [SlideLayoutType](../../slidelayouttype)
* интерфейс [IGlobalLayoutSlideCollection](../../igloballayoutslidecollection)
* пространство имен [Aspose.Slides](../../igloballayoutslidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->