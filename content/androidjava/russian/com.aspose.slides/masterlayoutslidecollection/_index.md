---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию всех макетных слайдов определённого мастер-слайда.
type: docs
url: /ru/com.aspose.slides/masterlayoutslidecollection/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Представляет коллекцию всех макетных слайдов определённого мастер-слайда. Наследует класс LayoutSlideCollection и предоставляет методы для добавления/вставки/удаления/клонирования/перестановки макетных слайдов в контексте отдельных коллекций макетных слайдов мастера.
## Методы

| Метод | Описание |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Добавляет копию указанного макетного слайда в конец коллекции. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Вставляет копию указанного макетного слайда в указанную позицию коллекции. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Добавляет новый макетный слайд в конец коллекции. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Вставляет новый макетный слайд в указанную позицию коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Перемещает макетный слайд из коллекции в указанную позицию. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Добавляет копию указанного макетного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |

--------------------

1) Новый макет будет связан с родительским мастер-слайдом этой коллекции макетных слайдов. Это аналог операции копировать/вставить с опцией «Использовать тему назначения» в PowerPoint. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-), доступный через свойство ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). 

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Вставляет копию указанного макетного слайда в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |

--------------------

Новый макет будет связан с родительским мастер-слайдом этой коллекции макетных слайдов. Это аналог операции копировать/вставить с опцией «Использовать тему назначения» в PowerPoint. 

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Вставленный слайд.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Добавляет новый макетный слайд в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layoutType | byte | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Имя нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан null, имя будет сгенерировано автоматически в зависимости от переданного типа макета (например, «Title Slide», «1_Title Slide», «2_…» и т.д.). |

--------------------

1) Добавленный макет для значения SlideLayoutType.Custom не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-), доступный через свойство ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). 

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Вставляет новый макетный слайд в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| layoutType | byte | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Имя нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан null, имя будет сгенерировано автоматически в зависимости от переданного типа макета (например, «Title Slide», «1_Title Slide», «2_…» и т.д.). |

--------------------

Вставленный макет для значения SlideLayoutType.Custom не содержит заполнителей и фигур. 

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Вставленный слайд.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который необходимо удалить. |

--------------------

1) Чтобы избежать выброса PptxEditException, проверьте свойство HasDependingSlides макета заранее. 2) Вы также можете использовать метод [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) для упрощения кода. 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Перемещает макетный слайд из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Целевой индекс. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для перемещения. |