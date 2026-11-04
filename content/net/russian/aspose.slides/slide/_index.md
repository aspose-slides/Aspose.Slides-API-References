---
title: Slide
second_title: Aspose.Sildes для .NET справочник API
description: Представляет слайд в презентации.
type: docs
weight: 9980
url: /ru/aspose.slides/slide/
---
## Slide класс

Представляет слайд в презентации.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter слайда. Только для чтения [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Определяет, скрыт ли указанный слайд во время показа. Чтение/запись Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Возвращает или задает слайд макета для текущего слайда. Чтение/запись [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задает имя слайда. Чтение/запись String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Позволяет получить доступ к слайду заметок, добавить и удалить его. Только для чтения [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Чтение/запись Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Возвращает номер слайда. Индекс слайда в [`Slides`](../presentation/slides) коллекции всегда равен SlideNumber - Presentation.FirstSlideNumber. Чтение/запись Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, содержащий информацию о том, как указанный слайд продвигается во время показа. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Возвращает менеджер перекрывающей темы. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в заполнителе даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Возвращает объект Thumbnail Image (20% от реального размера). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Возвращает объект Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Возвращает объект Thumbnail tiff image с указанными параметрами. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Возвращает объект Thumbnail Image с указанным размером. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Возвращает объект Thumbnail Image с указанным размером. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Возвращает все комментарии слайда, добавленные конкретным автором. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Объединяет последовательности одинакового форматирования во всех абзацах всех подходящих фигур. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет последовательности одинакового форматирования во всех абзацах всех подходящих фигур. |
| [Remove](../../aspose.slides/slide/remove)() | Удаляет слайд из презентации. |
| [Reset](../../aspose.slides/slide/reset)() | Сбрасывает позицию, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Сохраняет содержание слайда в файл EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Сохраняет содержание слайда в файл SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержание слайда в файл SVG. |

### См. также

* класс [BaseSlide](../baseslide)
* интерфейс [ISlide](../islide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->