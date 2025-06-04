---
title: LayoutSlide
second_title: Aspose.Sildes для .NET API Reference
description: Представляет слайд макета.
type: docs
weight: 7400
url: /ru/aspose.slides/layoutslide/
---

## LayoutSlide class

Представляет слайд макета.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию ActiveX контролов на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Возвращает true, если существует хотя бы один слайд, который зависит от этого слайда макета. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Возвращает менеджер заголовков и нижних колонтитулов для слайда макета. Только для чтения [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Возвращает тип макета этого слайда макета. Только для чтения [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Возвращает или устанавливает мастер-слайд для макета. Чтение/запись [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или устанавливает имя слайда. Чтение/запись String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Возвращает менеджер заполнителей для слайда макета. Только для чтения [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах или нет. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, который содержит информацию о том, как указанный слайд переходит во время слайд-шоу. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Возвращает управляющий темами переопределения. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |

## Methods

| Name | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение вычисляется на основе структуры слайда и статического контента. Два слайда равны, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. Сравнение не учитывает значения уникальных идентификаторов, например, SlideId и динамического контента, например, значения текущей даты в заполнителе даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Возвращает массив со всеми слайдами, которые зависят от этого слайда макета. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет части с одинаковым форматированием во всех абзацах во всех допустимых фигурах. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет части с одинаковым форматированием во всех абзацах во всех допустимых фигурах. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Удаляет макет из презентации. |

### See Also

* class [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->