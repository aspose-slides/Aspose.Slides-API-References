---
title: Slide class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/slide/
---
## Slide класс

Представляет слайд в презентации.

**Наследование:**[`Slide`](/slides/python-net/ru/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)

Тип Slide предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`shapes`](/slides/python-net/ru/aspose.slides/slide/shapes/) | Возвращает фигуры слайда.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ru/aspose.slides/slide/controls/) | Возвращает коллекцию элементов управления ActiveX на слайде.<br/>            Только для чтения [`IControlCollection`](/slides/python-net/ru/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ru/aspose.slides/slide/name/) | Возвращает или задает имя слайда.<br/>            Чтение/запись **str**. |
| [`slide_id`](/slides/python-net/ru/aspose.slides/slide/slide_id/) | Возвращает идентификатор слайда.<br/>            Только для чтения **int**. |
| [`custom_data`](/slides/python-net/ru/aspose.slides/slide/custom_data/) | Возвращает пользовательские данные слайда.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ru/aspose.slides/slide/timeline/) | Возвращает объект временной шкалы анимации.<br/>            Только для чтения [`IAnimationTimeLine`](/slides/python-net/ru/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/slide/slide_show_transition/) | Возвращает объект Transition, который содержит информацию о<br/>            том, как указанный слайд продвигается во время показа слайдов.<br/>            Только для чтения [`ISlideShowTransition`](/slides/python-net/ru/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ru/aspose.slides/slide/background/) | Возвращает фон слайда.<br/>            Только для чтения [`IBackground`](/slides/python-net/ru/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/slide/hyperlink_queries/) | Обеспечивает простой доступ к содержащимся гиперссылкам.<br/>            Только для чтения [`IHyperlinkQueries`](/slides/python-net/ru/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/slide/show_master_shapes/) | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет.<br/>            Чтение/запись **bool**. |
| [`presentation`](/slides/python-net/ru/aspose.slides/slide/presentation/) | Возвращает интерфейс IPresentation.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/slide/header_footer_manager/) | Возвращает менеджер HeaderFooter слайда.<br/>            Только для чтения [`ISlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/slide/theme_manager/) | Возвращает менеджер переопределяющей темы.<br/>            Только для чтения [`IOverrideThemeManager`](/slides/python-net/ru/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/ru/aspose.slides/slide/slide_number/) | Возвращает номер слайда.<br/>            Индекс слайда в коллекции [`Presentation.slides`](/slides/python-net/ru/aspose.slides/presentation/slides) всегда равен SlideNumber - Presentation.FirstSlideNumber.<br/>            Чтение/запись **int**. |
| [`hidden`](/slides/python-net/ru/aspose.slides/slide/hidden/) | Определяет, скрыт ли указанный слайд во время показа слайдов.<br/>            Чтение/запись **bool**. |
| [`layout_slide`](/slides/python-net/ru/aspose.slides/slide/layout_slide/) | Возвращает или задает макетный слайд для текущего слайда.<br/>            Чтение/запись [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ru/aspose.slides/slide/notes_slide_manager/) | Позволяет получать доступ к слайду заметок, добавлять и удалять его.<br/>            Только для чтения [`INotesSlideManager`](/slides/python-net/ru/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/ru/aspose.slides/slide/slide/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/slide/join_portions_with_same_formatting/#) | Объединяет сегменты с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ru/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Объединяет сегменты с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/slide/get_image/#float-float) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/slide/get_image/#) | Возвращает объект Thumbnail Image (20 % реального размера). |
| [`get_image(self, image_size)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposepydrawingsize) | Возвращает объект Thumbnail Image с указанным размером. |
| [`get_image(self, options)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Возвращает объект Thumbnail tiff image с указанными параметрами. |
| [`get_image(self, options)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Возвращает объект Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [`get_image(self, options, image_size)`](/slides/python-net/ru/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Возвращает объект Thumbnail Image с указанным размером. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/slide/write_as_svg/#iorawiobase) | Сохраняет содержимое слайда в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое слайда в файл SVG. |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/slide/equals/#ibaseslide) | Определяет, равны ли два экземпляра IBaseSlide.<br/>            Возвращаемое значение вычисляется на основе структуры слайда и статического контента.<br/>            Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т.д. одинаковы. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамический контент, например текущее значение даты в заполнитель даты. |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/slide/create_theme_effective/#) | Возвращает эффективную тему для этого слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/slide/find_shape_by_alt_text/#str) | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [`write_as_emf(self, stream)`](/slides/python-net/ru/aspose.slides/slide/write_as_emf/#iorawiobase) | Сохраняет содержимое слайда в файл EMF. |
| [`remove(self)`](/slides/python-net/ru/aspose.slides/slide/remove/#) | Удаляет слайд из презентации. |
| [`reset(self)`](/slides/python-net/ru/aspose.slides/slide/reset/#) | Сбрасывает позицию, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/ru/aspose.slides/slide/get_slide_comments/#icommentauthor) | Возвращает все комментарии к слайду, добавленные определённым автором. |

### См. также
* класс [`BaseSlide`](/slides/python-net/ru/aspose.slides/baseslide)
* класс [`Slide`](/slides/python-net/ru/aspose.slides/slide)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)