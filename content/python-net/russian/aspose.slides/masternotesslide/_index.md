---
title: MasterNotesSlide class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/masternotesslide/
---
## MasterNotesSlide класс

Представляет главный слайд для заметок.

**Наследование:**[`MasterNotesSlide`](/slides/python-net/ru/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

Тип MasterNotesSlide раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/masternotesslide/shapes/) | Returns the shapes of a slide.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/masternotesslide/controls/) | Returns the collection of ActiveX controls on a slide.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/masternotesslide/name/) | Returns or sets the name of a slide.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/masternotesslide/slide_id/) | Returns the ID of a slide.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/masternotesslide/custom_data/) | Returns the slide's custom data.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/masternotesslide/timeline/) | Returns animation timeline object.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/masternotesslide/slide_show_transition/) | Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/masternotesslide/background/) | Returns slide's background.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/masternotesslide/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/masternotesslide/show_master_shapes/) | Specifies if shapes on the master slide should be shown on slides or not.<br/>            For master slide itself this property always returns `false`.<br/>            Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/masternotesslide/presentation/) | Returns IPresentation interface.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/masternotesslide/header_footer_manager/) | Returns HeaderFooter manager of the master notes slide.<br/>            Только для чтения [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/masternotesslide/theme_manager/) | Returns the theme manager.<br/>            Только для чтения [`IMasterThemeManager`](/slides/python-net/ru/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/ru/aspose.slides/masternotesslide/notes_style/) | Returns the style of a notes text.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/ru/aspose.slides/masternotesslide/drawing_guides/) | Returns a collection of drawing guides for the master notes slide.<br/>            Только для чтения [`IDrawingGuidesCollection`](/slides/python-net/ru/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ru/aspose.slides/masternotesslide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Объединяет последовательности с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Объединяет последовательности с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/masternotesslide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого.<br/>            Слайды считаются равными, если все формы, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущая дата в заполнителе даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/masternotesslide/create_theme_effective/#) | Возвращает эффективную тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |


### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`MasterNotesSlide`](/slides/python-net/ru/aspose.slides/masternotesslide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)