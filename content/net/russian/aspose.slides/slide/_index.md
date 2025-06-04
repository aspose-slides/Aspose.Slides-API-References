---
title: Slide
second_title: Aspose.Sildes для .NET Справочник API
description: Представляет слайд в презентации.
type: docs
weight: 9650
url: /ru/aspose.slides/slide/
---

## Класс Slide

Представляет слайд в презентации.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Свойства

| Название | Описание |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Возвращает фон слайда. Только для чтения [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Возвращает пользовательские данные слайда. Только для чтения [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Возвращает менеджер заголовков и нижних колонтитулов слайда. Только для чтения [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Определяет, скрыт ли указанный слайд во время показа слайдов. Читается/записывается Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Обеспечивает быстрый доступ к содержащимся гиперссылкам. Только для чтения [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Возвращает или задает слайд макета для текущего слайда. Читается/записывается [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Возвращает или задает имя слайда. Читается/записывается String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Позволяет получить доступ к слайду заметок, добавлять и удалять его. Только для чтения [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Возвращает интерфейс IPresentation. Только для чтения [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Возвращает фигуры слайда. Только для чтения [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Указывает, следует ли отображать фигуры на главном слайде на слайдах или нет. Читается/записывается Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Возвращает ID слайда. Только для чтения UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Возвращает номер слайда. Индекс слайда в коллекции [`Slides`](../presentation/slides) всегда равен SlideNumber - Presentation.FirstSlideNumber. Читается/записывается Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Возвращает объект Transition, который содержит информацию о том, как указанный слайд переходит во время показа слайдов. Только для чтения [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Возвращает управляющий темами. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Возвращает объект временной шкалы анимации. Только для чтения [`IAnimationTimeLine`](../ianimationtimeline). |

## Методы

| Название | Описание |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Возвращает эффективную тему для этого слайда. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого. Два слайда равны, если все фигуры, стили, тексты, анимация и другие параметры и т. д. равны. Сравнение не учитывает значения уникального идентификатора, например, SlideId и динамическое содержимое, например, текущее значение даты в Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Возвращает объект изображения эскиза (20% от реального размера). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Возвращает объект изображения эскиза. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Возвращает объект изображения эскиза в формате tiff с заданными параметрами. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Возвращает объект изображения эскиза с заданным размером. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Возвращает объект изображения эскиза с пользовательским масштабированием. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Возвращает объект изображения эскиза с указанным размером. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Возвращает объект изображения эскиза с пользовательским масштабированием. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Возвращает все комментарии слайда, добавленные конкретным автором. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Объединяет части с одинаковым форматированием во всех абзацах во всех приемлемых фигурах. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Объединяет части с одинаковым форматированием во всех абзацах во всех приемлемых фигурах. |
| [Remove](../../aspose.slides/slide/remove)() | Удаляет слайд из презентации. |
| [Reset](../../aspose.slides/slide/reset)() | Сбрасывает позицию, размер и форматирование каждой фигуры, которая имеет прототип на LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Сохраняет содержимое слайда в файл EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Сохраняет содержимое слайда в файл SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое слайда в файл SVG. |

### Смотрите также

* класс [BaseSlide](../baseslide)
* интерфейс [ISlide](../islide)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->