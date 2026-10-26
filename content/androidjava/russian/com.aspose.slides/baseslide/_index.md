---
title: BaseSlide
second_title: Справка по API Aspose.Slides для Android через Java
description: Представляет общие данные для всех типов слайдов.
type: docs
url: /ru/com.aspose.slides/baseslide/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Представляет общие данные для всех типов слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [getShapes()](#getShapes--) | Возвращает формы слайда. |
| [getControls()](#getControls--) | Возвращает коллекцию элементов управления ActiveX на слайде. |
| [getName()](#getName--) | Возвращает или задает имя слайда. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задает имя слайда. |
| [getSlideId()](#getSlideId--) | Возвращает ID слайда. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Определяет, равны ли два экземпляра IBaseSlide. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет фрагменты текста с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Объединяет фрагменты текста с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| [createThemeEffective()](#createThemeEffective--) | Возвращает эффективную тему для этого слайда. |
| [getCustomData()](#getCustomData--) | Возвращает пользовательские данные слайда. |
| [getTimeline()](#getTimeline--) | Возвращает объект временной шкалы анимации. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит в режиме показа слайдов. |
| [getBackground()](#getBackground--) | Возвращает фон слайда. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Обеспечивает простой доступ к содержащимся гиперссылкам. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, следует ли отображать фигуры на слайде-мастере на слайдах. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, следует ли отображать фигуры на слайде-мастере на слайдах. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Возвращает интерфейс IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Возвращает формы слайда. Только для чтения [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Возвращаемое значение:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Возвращаемое значение:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Возвращает или задает имя слайда. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Возвращает или задает имя слайда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Возвращает ID слайда. Только для чтения long.

**Возвращаемое значение:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического контента. Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие параметры и т.д. одинаковы. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамический контент, например текущее значение даты в заполнителе Date Placeholder.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide для сравнения с текущим IBaseSlide. |

**Возвращаемое значение:**
boolean -  **true**  если указанный IBaseSlide равен текущему IBaseSlide; в противном случае  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Объединяет фрагменты текста с одинаковым форматированием во всех абзацах всех приемлемых фигур.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Объединяет фрагменты текста с одинаковым форматированием во всех абзацах всех приемлемых фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Возвращает эффективную тему для этого слайда.

**Возвращаемое значение:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Возвращает пользовательские данные слайда. Только для чтения [ICustomData](../../com.aspose.slides/icustomdata).

**Возвращаемое значение:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Возвращает объект временной шкалы анимации. Только для чтения [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Возвращаемое значение:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит в режиме показа слайдов. Только для чтения [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Возвращаемое значение:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Возвращает фон слайда. Только для чтения [IBackground](../../com.aspose.slides/ibackground).

**Возвращаемое значение:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Возвращаемое значение:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Указывает, следует ли отображать фигуры на слайде-мастере на слайдах. Для самого слайда-мастера это свойство всегда возвращает false. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Указывает, следует ли отображать фигуры на слайде-мастере на слайдах. Для самого слайда-мастера это свойство всегда возвращает false. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Находит первое вхождение фигуры с указанным альтернативным текстом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| altText | java.lang.String | Альтернативный текст. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - объект Shape или null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает интерфейс IPresentation. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает базовый слайд. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)