---
title: GlobalLayoutSlideCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию всех слайдов макета в презентации.
type: docs
url: /ru/com.aspose.slides/globallayoutslidecollection/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Все реализованные интерфейсы:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Представляет коллекцию всех слайдов макета в презентации. Расширяет класс LayoutSlideCollection методами для добавления/клонирования слайдов макета в контексте объединения отдельных коллекций мастеров макетов.

## Методы

| Метод | Описание |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Добавляет копию указанного слайда макета в презентацию. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Добавляет копию указанного слайда макета в презентацию. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Добавляет новый слайд макета в презентацию. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Добавляет копию указанного слайда макета в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |

--------------------

При клонировании макета между разными презентациями мастер-макет также может быть клонирован, чтобы сохранить исходное форматирование. Для отслеживания автоматически клонированных мастеров используется внутренний реестр, чтобы предотвратить создание нескольких копий одного и того же слайда-мастера. Ручное клонирование слайдов-мастеров ни предотвращается, ни регистрируется.

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Добавляет копию указанного слайда макета в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд-мастер для нового макета. |

--------------------

1) Новый макет будет связан с определённым мастером в целевой презентации. Таким образом, это аналог копирования/вставки с опцией «Use Destination Theme» в PowerPoint. 2) Аналогом этого метода является метод [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-), доступный через свойство ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Добавляет новый слайд макета в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Слайд-мастер для нового макета. |
| layoutType | byte | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов в настоящее время не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Имя для нового макета. Если переданное имя уже используется, будет выброшено ArgumentException. Если передан параметр null, имя будет сгенерировано автоматически в зависимости от переданного типа макета (например, «Title Slide» или «1_Title Slide», «2_..» и т.д.). |

--------------------

1) Добавленный макет для значения SlideLayoutType.Custom параметра layoutType не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-), доступный через свойство ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.