---
title: Slide
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет слайд в презентации.
type: docs
weight: 9180
url: /ru/aspose.slides/slide/
---
## Slide class

Представляет слайд в презентации.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только чтение[`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает набор элементов управления ActiveX на слайде. Только для чтения[`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения[`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Возвращает менеджер HeaderFooter слайда. Только для чтения[`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Определяет, будет ли указанный слайд скрыт во время показа слайдов. Чтение/записьBoolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает легкий доступ к содержащимся гиперссылкам. Только для чтения[`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Возвращает или задает макет слайда для текущего слайда. Чтение/запись[`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задает имя слайда. Чтение/записьString. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Разрешить доступ к слайду заметок, добавлять и удалять его. Только для чтения[`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только чтение[`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает формы слайда. Только чтение[`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах или нет. Чтение/записьBoolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает идентификатор слайда. Только для чтенияUInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Возвращает номер слайда. Индекс слайда в коллекции[`Slides`](../presentation/slides)всегда равен SlideNumber - Presentation.FirstSlideNumber. Чтение/записьInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, который содержит информацию о продвижении указанного слайда во время показа слайдов. Только для чтения[`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Возвращает приоритетный менеджер тем. Только для чтения[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения[`IAnimationTimeLine`](../ianimationtimeline). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда равны, если все формы, стили, тексты, анимация и другие настройки. и т. д. равны. При сравнении не учитываются значения уникальных идентификаторов, например SlideId, и динамическое содержимое, например текущее значение даты в заполнителе даты. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Возвращает все комментарии к слайдам, добавленные определенным автором. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail)() | Возвращает объект Thumbnail Image (20% реального размера). |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_4)(IRenderingOptions) | Возвращает объект Thumbnail Bitmap. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_7)(ITiffOptions) | Возвращает растровый объект Thumbnail tiff с указанными параметрами. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_9)(Size) | Возвращает объект Thumbnail Bitmap указанного размера. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_8)(float, float) | Возвращает объект Thumbnail Bitmap с пользовательским масштабированием. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_6)(IRenderingOptions, Size) | Возвращает объект Thumbnail Bitmap указанного размера. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_5)(IRenderingOptions, float, float) | Возвращает объект Thumbnail Bitmap с пользовательским масштабированием. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Соединения выполняются с одинаковым форматированием во всех абзацах во всех допустимых формах. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Соединения выполняются с одинаковым форматированием во всех абзацах во всех допустимых формах. |
| [Remove](../../aspose.slides/slide/remove)() | Удаляет слайд из презентации. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_3)(IRenderingOptions, Graphics) | Визуализирует определенный слайд в объект Graphics. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_5)(IRenderingOptions, Graphics, Size) | Визуализирует определенный слайд в объект Graphics, используя указанный размер. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_4)(IRenderingOptions, Graphics, float, float) | Визуализирует определенный слайд в объект Graphics с пользовательским масштабированием. |
| [Reset](../../aspose.slides/slide/reset)() | Сбрасывает положение, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Сохраняет содержимое слайда в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое слайда в виде файла SVG. |

### Смотрите также

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
