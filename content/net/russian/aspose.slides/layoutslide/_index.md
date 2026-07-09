---
title: LayoutSlide
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет макетный слайд.
type: docs
weight: 7640
url: /ru/aspose.slides/layoutslide/
---
## LayoutSlide класс

Представляет слайд макета.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Возвращает коллекцию направляющих для макетного слайда. Только для чтения [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Возвращает true, если существует хотя бы один слайд, зависящий от этого макетного слайда. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter макетного слайда. Только для чтения [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Возвращает тип макета этого макетного слайда. Только для чтения [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Возвращает или задает основной слайд для макета. Чтение/запись [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задает имя слайда. Чтение/запись String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Возвращает менеджер заполнителей макетного слайда. Только для чтения [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на основном слайде отображаться на слайдах или нет. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, который содержит информацию о том, как указанный слайд переходит во время показа слайдов. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Возвращает менеджер переопределяющей темы. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. Сравнение не учитывает уникальные идентификаторы, такие как SlideId, и динамическое содержимое, например текущее значение даты в заполнителе Date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Возвращает массив всех слайдов, которые зависят от этого макетного слайда. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет сегменты с одинаковым форматированием во всех абзацах всех подходящих фигур. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет сегменты с одинаковым форматированием во всех абзацах во всех подходящих фигурах. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Удаляет макет из презентации. |

### См. также

* класс [BaseSlide](../baseslide)
* интерфейс [ILayoutSlide](../ilayoutslide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->