---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides для Android через Java API
description: Представляет коллекцию всех слайдов макета в презентации.
type: docs
url: /ru/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Представляет коллекцию всех слайдов макета в презентации. Расширяет интерфейс ILayoutSlideCollection методами добавления/клонирования слайдов макета в контексте объединения отдельных коллекций макетов мастера.

## Методы

| Метод | Описание |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Добавляет копию указанного слайда макета в презентацию. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Добавляет копию указанного слайда макета в презентацию. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Добавляет новый слайд макета в презентацию. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Добавляет копию указанного слайда макета в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |

--------------------

При клонировании макета между разными презентациями мастер макета также может быть клонирован, чтобы сохранить исходное форматирование. Внутренний реестр используется для отслеживания автоматически клонированных мастеров с целью предотвращения создания нескольких копий одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. |

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Добавляет копию указанного слайда макета в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд для нового макета. |

--------------------

Новый макет будет связан с определённым мастером в целевой презентации. Таким образом это аналог операции копировать/вставить с опцией «Использовать тему назначения» в PowerPoint. |

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Добавляет новый слайд макета в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд для нового макета. |
| layoutType | byte | Тип макета для нового макета. Поддерживаемые типы макетов: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Другие типы макетов сейчас не поддерживаются: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Имя для нового макета. Если переданное имя уже используется, будет выброшено исключение ArgumentException. Если передан параметр null, имя будет сгенерировано автоматически с учётом переданного типа макета (например «Title Slide» или «1_Title Slide», «2_…» и т.д.). |

--------------------

1) Добавленный макет для значения SlideLayoutType.Custom в параметре layoutType не содержит заполнителей и фигур. 2) Аналогом этого метода является метод [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) доступный через свойство ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Добавленный слайд.