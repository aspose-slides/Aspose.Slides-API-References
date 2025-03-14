---
title: Add
second_title: Справочник по API Aspose.Slides для .NET
description: Добавляет в презентацию новый макет слайда.
type: docs
weight: 10
url: /ru/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection.Add method

Добавляет в презентацию новый макет слайда.

```csharp
public ILayoutSlide Add(IMasterSlide master, SlideLayoutType layoutType, string layoutName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| master | IMasterSlide | Мастер-слайд для нового макета. |
| layoutType | SlideLayoutType | Тип макета для нового макета. Поддерживаемые типы макетов:Заголовок, Только заголовок, Пустой, Заголовок и объект, Вертикальный текст, Вертикальный заголовок и текст, Два объекта, Заголовок раздела, Два текста и два объекта, Заголовок и заголовок, Изображение и заголовок, Пользовательский. Другие типы макетов теперь не поддерживаются:Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText , TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | String | Имя для нового макета. Если переданное имя уже используется, будет сгенерировано исключение ArgumentException. Если передан нулевой параметр, то имя генерируется автоматически в соответствии с переданным типом макета (например, "Title Slide" или "1_Title Slide", "2_.." и т. д. ). |

### Возвращаемое значение

Добавлен слайд.

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | Брошен, если неподдерживаемое значение параметра*layoutType*передается. Типы макетов, которые сейчас не поддерживаются:Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, Вертикальный заголовок и текст над диаграммой, объект и два объекта, два объекта и объект. |
| ArgumentNullException | Вызывается, если*master*равно null. |
| ArgumentException | Брошен, если*master*принадлежит другая презентация. |
| ArgumentException | Вызывается, если значение имени макета*layoutName*уже используется в коллекции макетов*master*. |

### Примечания

1) Добавлен макет для значения SlideLayoutType.Custom of*layoutType* не содержит заполнителей и форм. 2) Аналогом этого метода является метод[`Add`](../../imasterlayoutslidecollection/add) доступ осуществляется с помощью свойства[`LayoutSlides`](../../imasterslide/layoutslides).

### Смотрите также

* interface [ILayoutSlide](../../ilayoutslide)
* interface [IMasterSlide](../../imasterslide)
* enum [SlideLayoutType](../../slidelayouttype)
* class [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* пространство имен [Aspose.Slides](../../globallayoutslidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
