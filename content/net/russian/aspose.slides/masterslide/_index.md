---
title: MasterSlide
second_title: Aspose.Sildes для справки по API .NET
description: Представляет ведущее слайд в презентации.
type: docs
weight: 7780
url: /ru/aspose.slides/masterslide/
---

## MasterSlide class

Представляет ведущее слайд в презентации.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Свойства

| Название | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Возвращает стиль основного текста. Только для чтения [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Возвращает true, если существует хотя бы один слайд, который зависит от этого ведущего слайда. Только для чтения Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Возвращает менеджер заголовков и подвалов для ведущего слайда. Только для чтения [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает простой доступ к содержащимся гиперссылка. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Возвращает коллекцию дочерних макетов слайдов для этого ведущего слайда. Только для чтения [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Возвращает или задает имя ведущего слайда. Чтение/запись String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Возвращает стиль другого текста. Только для чтения [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Определяет, следует ли удалять соответствующий мастер, когда все слайды, следующие за этим мастером, удаляются. Примечание: Aspose.Slides никогда не удаляет неиспользуемый мастер самостоятельно; для фактического удаления неиспользуемых мастеров вызовите [`RemoveUnused`](../masterslidecollection/removeunused) Чтение/запись Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на ведущем слайде отображаться на слайдах или нет. Для самого ведущего слайда это свойство всегда возвращает `false`. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объекта Transition, который содержит информацию о том, как указанный слайд переходит во время показа слайдов. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Возвращает менеджер тем. Только для чтения [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Возвращает стиль текста заголовка. Только для чтения [`ITextStyle`](../itextstyle). |

## Методы

| Название | Описание |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Создает новый ведущий слайд на основе текущего, применяя к нему внешнюю тему, и применяет созданный ведущий слайд ко всем зависимым слайдам. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержания. Два слайда равны, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. Сравнение не учитывает значения уникального идентификатора, например, SlideId и динамическое содержание, например, текущее значение даты в Заполнителе даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Возвращает массив со всеми слайдами, которые зависят от этого ведущего слайда. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет части с одинаковым форматированием во всех параграфах для всех допустимых фигур. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет части с одинаковым форматированием во всех параграфах для всех допустимых фигур. |

### См. также

* класс [BaseSlide](../baseslide)
* интерфейс [IMasterSlide](../imasterslide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->