---
title: MasterSlide
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет мастер-слайд в презентации.
type: docs
weight: 7320
url: /ru/net/aspose.slides/masterslide/
---
## MasterSlide class

Представляет мастер-слайд в презентации.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения[`IBackground`](../ibackground) . |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Возвращает стиль основного текста. Только для чтения[`ITextStyle`](../itextstyle) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения[`ICustomData`](../icustomdata) . |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Возвращает значение true, если существует хотя бы один слайд, зависящий от этого эталонного слайда. Только для чтенияBoolean . |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter мастер-слайда. Только для чтения[`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает легкий доступ к содержащимся гиперссылкам. Только для чтения[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Возвращает коллекцию дочерних слайдов макета для этого мастер-слайда. Только для чтения[`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection) . |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Возвращает или задает имя мастер-слайда. Чтение/записьString . |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Возвращает стиль другого текста. Только для чтения[`ITextStyle`](../itextstyle) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения[`IPresentation`](../ipresentation) . |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Определяет, удаляется ли соответствующий мастер, когда удаляются все слайды, следующие за этим мастером. Примечание. Aspose.Slides никогда не удалит неиспользуемый мастер сам по себе.[`RemoveUnused`](../masterslidecollection/removeunused) Чтение/записьBoolean . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает формы слайда. Только для чтения[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах или нет. Для самого мастер-слайда это свойство всегда возвращает значение.`ЛОЖЬ` . Чтение/записьBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает идентификатор слайда. Только для чтенияUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект перехода, который содержит информацию о том, как продвигается указанный слайд во время показа слайдов. Только для чтения[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Возвращает менеджер тем. Только для чтения[`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения[`IAnimationTimeLine`](../ianimationtimeline) . |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Возвращает стиль текста заголовка. Только для чтения[`ITextStyle`](../itextstyle) . |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Создает новый мастер-слайд на основе текущего, применяя к нему внешнюю тему и применяет созданный мастер-слайд ко всем зависимым слайдам. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все формы, стили, тексты, анимация и другие настройки. и т. д. равны. При сравнении не учитываются значения уникальных идентификаторов, например SlideId и динамическое содержимое, например текущее значение даты в заполнителе даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Возвращает массив со всеми слайдами, которые зависят от этого мастер-слайда. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Объединяет прогоны с одинаковым форматированием во всех абзацах всех допустимых форм. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Соединения выполняются с одинаковым форматированием во всех абзацах во всех допустимых формах. |

### Смотрите также

* class [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
