---
title: IBaseSlide
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет общие данные для всех типов слайдов.
type: docs
url: /ru/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Представляет общие данные для всех типов слайдов.
## Методы

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Возвращает фигуры слайда. |
| [getControls()](#getControls--) | Возвращает коллекцию элементов управления ActiveX на слайде. |
| [getName()](#getName--) | Возвращает или задает имя слайда. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задает имя слайда. |
| [getSlideId()](#getSlideId--) | Возвращает идентификатор слайда. |
| [getCustomData()](#getCustomData--) | Возвращает пользовательские данные слайда. |
| [getTimeline()](#getTimeline--) | Возвращает объект временной шкалы анимации. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Возвращает объект TransitionEx, содержащий информацию о том, как указанный слайд переходит во время показа. |
| [getBackground()](#getBackground--) | Возвращает фон слайда. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Обеспечивает простой доступ к содержащимся гиперссылкам. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли фигуры на слайде-шаблоне отображаться на слайдах или нет. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли фигуры на слайде-шаблоне отображаться на слайдах или нет. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет отрезки текста с одинаковым форматированием во всех абзацах во всех допустимых фигурах. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Определяет, равны ли два экземпляра IBaseSlide. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Возвращает фигуры слайда. Только для чтения [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Возвращает:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Возвращает:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает или задает имя слайда. Чтение/запись String.

**Возвращает:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Возвращает или задает имя слайда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Возвращает идентификатор слайда. Только для чтения long.

**Возвращает:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Возвращает пользовательские данные слайда. Только для чтения [ICustomData](../../com.aspose.slides/icustomdata).

**Возвращает:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Возвращает объект временной шкалы анимации. Только для чтения [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Возвращает:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Возвращает объект TransitionEx, содержащий информацию о том, как указанный слайд переходит во время показа. Только для чтения [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Возвращает:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Возвращает фон слайда. Только для чтения [IBackground](../../com.aspose.slides/ibackground).

**Возвращает:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Возвращает:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Указывает, должны ли фигуры на слайде-шаблоне отображаться на слайдах или нет. Для самого слайда-шаблона это свойство всегда возвращает false. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Указывает, должны ли фигуры на слайде-шаблоне отображаться на слайдах или нет. Для самого слайда-шаблона это свойство всегда возвращает false. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Находит первое вхождение фигуры с указанным альтернативным текстом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| altText | java.lang.String | Alternative text. |
**Возвращает:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Объединяет отрезки текста с одинаковым форматированием во всех абзацах во всех допустимых фигурах.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, такие как SlideId, и динамическое содержимое, например текущее значение даты в заполнителе даты.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |
**Возвращает:**
boolean - **true** if the specified IBaseSlide is equal to the current IBaseSlide; otherwise, **false**.