---
title: Slide
second_title: Aspose.Sildes для .NET: справка API
description: Представляет слайд в презентации.
type: docs
weight: 9960
url: /ru/aspose.slides/slide/
---
## Класс Slide

Представляет слайд в презентации.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только чтение [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только чтение [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только чтение [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter слайда. Только чтение [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Определяет, скрыт ли указанный слайд во время показа слайдов. Чтение/запись Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает простой доступ к содержащимся гиперссылкам. Только чтение [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Возвращает или задает слайд макета для текущего слайда. Чтение/запись [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задает имя слайда. Чтение/запись String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Позволяет получить доступ к слайду заметок, добавить и удалить его. Только чтение [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только чтение [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только чтение [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах или нет. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает идентификатор слайда. Только чтение UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Возвращает номер слайда. Индекс слайда в коллекции [`Slides`](../presentation/slides) всегда равен SlideNumber - Presentation.FirstSlideNumber. Чтение/запись Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, содержащий информацию о том, как указанный слайд продвигается во время показа слайдов. Только чтение [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Возвращает менеджер переопределяющей темы. Только чтение [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только чтение [`IAnimationTimeLine`](../ianimationtimeline). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. Сравнение не учитывает уникальные идентификаторы, например SlideId, и динамическое содержание, например текущее значение даты в Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Возвращает объект Thumbnail Image (20% от реального размера). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Возвращает объект Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Возвращает объект миниатюры tiff изображения с указанными параметрами. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Возвращает объект Thumbnail Image с указанным размером. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Возвращает объект Thumbnail Image с указанным размером. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Возвращает все комментарии к слайду, добавленные конкретным автором. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Объединяет участки текста с одинаковым форматированием во всех абзацах во всех подходящих фигурах. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет участки текста с одинаковым форматированием во всех абзацах во всех подходящих фигурах. |
| [Remove](../../aspose.slides/slide/remove)() | Удаляет слайд из презентации. |
| [Reset](../../aspose.slides/slide/reset)() | Сбрасывает позицию, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Сохраняет содержимое слайда в файл EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Сохраняет содержимое слайда в файл SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое слайда в файл SVG. |

### См. также

* класс [BaseSlide](../baseslide)
* интерфейс [ISlide](../islide)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->