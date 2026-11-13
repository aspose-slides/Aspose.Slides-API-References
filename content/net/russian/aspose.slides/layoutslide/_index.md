---
title: LayoutSlide
second_title: Aspose.Sildes для .NET справки API
description: Представляет слайд макета.
type: docs
weight: 7660
url: /ru/aspose.slides/layoutslide/
---
## Класс LayoutSlide

Представляет слайд макета.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию ActiveX-элементов управления на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Возвращает коллекцию руководящих линий рисования для слайда макета. Только для чтения [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Возвращает **true**, если существует хотя бы один слайд, зависящий от этого слайда макета. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter слайда макета. Только для чтения [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Предоставляет простой доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Возвращает тип макета этого слайда макета. Только для чтения [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Возвращает или задаёт главный слайд для макета. Чтение/запись [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задаёт имя слайда. Чтение/запись String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Возвращает менеджер заполнителей слайда макета. Только для чтения [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает формы слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Указывает, должны ли формы главного слайда отображаться на слайдах. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает идентификатор слайда. Только для чтения UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит в ходе показа. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Возвращает менеджер переопределяющей темы. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной линии анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение вычисляется на основе структуры слайда и статического контента. Два слайда равны, если все формы, стили, тексты, анимация и другие настройки и т.д. одинаковы. Сравнение не учитывает значения уникальных идентификаторов, например SlideId, и динамический контент, например текущее значение даты в заполнителе даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение формы с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Возвращает массив всех слайдов, зависящих от этого слайда макета. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет последовательности с одинаковым форматированием во всех абзацах всех приемлемых форм. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет последовательности с одинаковым форматированием во всех абзацах всех приемлемых форм. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Удаляет макет из презентации. |

### См. также

* класс [BaseSlide](../baseslide)
* интерфейс [ILayoutSlide](../ilayoutslide)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->