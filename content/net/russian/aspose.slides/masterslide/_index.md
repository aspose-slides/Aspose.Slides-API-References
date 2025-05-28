---
title: MasterSlide
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет собой мастер-слайд в презентации.
type: docs
weight: 7780
url: /ru/aspose.slides/masterslide/
---

## Класс MasterSlide

Представляет собой мастер-слайд в презентации.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Возвращает стиль основного текста. Только для чтения [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Возвращает true, если существует хотя бы один слайд, который зависит от этого мастер-слайда. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Возвращает менеджер заголовков и подвалов мастер-слайда. Только для чтения [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает легкий доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Возвращает коллекцию дочерних макетов слайдов для этого мастер-слайда. Только для чтения [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Возвращает или задает имя мастер-слайда. Чтение/запись String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Возвращает стиль другого текста. Только для чтения [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Определяет, будет ли соответствующий мастер удален, когда все слайды, следующие за этим мастером, будут удалены. Примечание: Aspose.Slides никогда не удалит какие-либо неиспользуемые мастера самостоятельно, чтобы фактически удалить неиспользуемые мастера, вызовите [`RemoveUnused`](../masterslidecollection/removeunused) Чтение/запись Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах или нет. Для самого мастер-слайда это свойство всегда возвращает `false`. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, который содержит информацию о том, как указанный слайд переходит во время показа слайдов. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Возвращает менеджер тем. Только для чтения [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Возвращает стиль заголовка текста. Только для чтения [`ITextStyle`](../itextstyle). |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Создает новый мастер-слайд на основе текущего, применяя к нему внешнюю тему и применяет созданный мастер-слайд ко всем зависимым слайдам. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все фигуры, стили, тексты, анимация и другие настройки и т. д. равны. Сравнение не учитывает значения уникальных идентификаторов, например SlideId, и динамическое содержимое, например текущее значение даты в плейсхолдере даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Возвращает массив со всеми слайдами, которые зависят от этого мастер-слайда. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет сегменты с одинаковым форматированием во всех абзацах для всех допустимых фигур. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет сегменты с одинаковым форматированием во всех абзацах для всех допустимых фигур. |

### Также смотрите

* класс [BaseSlide](../baseslide)
* интерфейс [IMasterSlide](../imasterslide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
