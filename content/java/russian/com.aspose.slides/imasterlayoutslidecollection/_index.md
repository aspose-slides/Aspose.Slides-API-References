---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides для Java API Reference
description: Представляет коллекцию всех слайдов макета определённого главного слайда.
type: docs
url: /ru/com.aspose.slides/imasterlayoutslidecollection/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Представляет коллекцию всех слайдов макета определённого главного слайда. Расширяет интерфейс ILayoutSlideCollection методами добавления/вставки/удаления/клонирования слайдов макета в контексте отдельных коллекций слайдов макета главного слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Добавляет копию указанного слайда макета в конец коллекции. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Вставляет копию указанного слайда макета в указанную позицию коллекции. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Добавляет новый слайд макета в конец коллекции. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Вставляет новый слайд макета в указанную позицию коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент с указанным индексом из коллекции. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Перемещает слайд макета из коллекции в указанную позицию. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Добавляет копию указанного слайда макета в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |

--------------------

1) Новый макет будет связан с родительским главным слайдом для этой коллекции слайдов макета. Таким образом это аналог копирования/вставки с опцией "Use Destination Theme" в PowerPoint. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-), доступный через свойство [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Вставляет копию указанного слайда макета в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |

--------------------

Новый макет будет связан с родительским главным слайдом для этой коллекции слайдов макета. Таким образом это аналог копирования/вставки с опцией "Use Destination Theme" в PowerPoint.

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Вставленный слайд.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Добавляет новый слайд макета в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layoutType | byte | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Имя для нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан параметр null, имя генерируется автоматически в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_.." и т.д.). |

--------------------

1) Добавленный макет для значения SlideLayoutType.Custom типа layoutType не содержит заполнителей и форм. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-), доступный через свойство [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Вставляет новый слайд макета в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| layoutType | byte | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Имя для нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан параметр null, имя генерируется автоматически в зависимости от переданного типа макета (например, "Title Slide" или "1_Title Slide", "2_.." и т.д.). |

--------------------

Вставленный макет для значения SlideLayoutType.Custom типа layoutType не содержит заполнителей и форм.

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Вставленный слайд.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент с указанным индексом из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который необходимо удалить. |

--------------------

1) Чтобы избежать выбрасывания PptxEditException, проверьте свойство HasDependingSlides макета заранее. 2) Вы также можете использовать метод [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) для упрощения кода.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Перемещает слайд макета из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Целевой индекс. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для перемещения. |