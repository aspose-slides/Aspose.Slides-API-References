---
title: MasterSlide
second_title: Aspose.Sildes для .NET справочник API
description: Представляет главный слайд в презентации.
type: docs
weight: 8050
url: /ru/aspose.slides/masterslide/
---
## MasterSlide класс

Представляет главный слайд в презентации.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Свойства

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Возвращает стиль основного текста. Только для чтения [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Возвращает коллекцию направляющих черчения для главного слайда. Только для чтения [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Возвращает true, если существует хотя бы один слайд, зависящий от этого главного слайда. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter главного слайда. Только для чтения [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Возвращает коллекцию дочерних макетных слайдов для этого главного слайда. Только для чтения [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Возвращает или задает имя главного слайда. Чтение/запись String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Возвращает стиль другого текста. Только для чтения [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Определяет, будет ли соответствующий мастер удалён, когда все слайды, следующие за этим мастером, удалены. Примечание: Aspose.Slides никогда не удалит ни один неиспользуемый мастер самостоятельно, чтобы действительно удалить неиспользуемые мастера, вызовите [`RemoveUnused`](../masterslidecollection/removeunused). Чтение/запись Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Указывает, следует ли отображать фигуры главного слайда на слайдах или нет. Для самого главного слайда это свойство всегда возвращает `false`. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит во время показа слайдов. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Возвращает менеджер тем. Только для чтения [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Возвращает стиль текста заголовка. Только для чтения [`ITextStyle`](../itextstyle). |

## Методы

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Создаёт новый главный слайд на основе текущего, применяя к нему внешнюю тему, и применяет созданный главный слайд ко всем зависимым слайдам. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Возвращает массив со всеми слайдами, зависящими от этого главного слайда. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет фрагменты с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет фрагменты с одинаковым форматированием во всех абзацах всех приемлемых фигур. |

### См. также

* класс [BaseSlide](../baseslide)
* интерфейс [IMasterSlide](../imasterslide)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->