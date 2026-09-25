---
title: ISlide class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/islide/
---
## ISlide класс

Представляет слайд в презентации.

Тип ISlide открывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/islide/header_footer_manager/) | Возвращает менеджер HeaderFooter слайда.<br/>            Только для чтения [`ISlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/ru/aspose.slides/islide/slide_number/) | Возвращает номер слайда.<br/>            Индекс слайда в коллекции [`IPresentation.slides`](/slides/python-net/ru/aspose.slides/ipresentation/slides) всегда равен SlideNumber - 1.<br/>            Чтение/запись **int**. |
| [`hidden`](/slides/python-net/ru/aspose.slides/islide/hidden/) | Определяет, скрыт ли указанный слайд во время показа слайдов.<br/>            Чтение/запись **bool**. |
| [`layout_slide`](/slides/python-net/ru/aspose.slides/islide/layout_slide/) | Возвращает или задает макетный слайд для текущего слайда.<br/>            Чтение/запись [`ILayoutSlide`](/slides/python-net/ru/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ru/aspose.slides/islide/notes_slide_manager/) | Позволяет получать доступ к слайду заметок, добавлять и удалять его.<br/>            Только для чтения [`INotesSlideManager`](/slides/python-net/ru/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/ru/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/ru/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/ru/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/ru/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ru/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/ru/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ru/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/islide/theme_manager/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/islide/get_image/#float-float) | Возвращает объект изображения с пользовательским масштабированием. |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/islide/get_image/#) | Возвращает объект эскизного изображения (20 % от реального размера). |
| [`get_image(self, image_size)`](/slides/python-net/ru/aspose.slides/islide/get_image/#asposeslidessize) | Возвращает объект изображения с указанным размером. |
| [`get_image(self, options)`](/slides/python-net/ru/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Возвращает объект эскизного tiff-битмапа с указанными параметрами. |
| [`get_image(self, options)`](/slides/python-net/ru/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Возвращает объект эскизного Bitmap. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Возвращает объект эскизного Bitmap с пользовательским масштабированием. |
| [`get_image(self, options, image_size)`](/slides/python-net/ru/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Возвращает объект эскизного Bitmap с указанным размером. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/islide/write_as_svg/#iorawiobase) | Сохраняет содержимое слайда в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое слайда в файл SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/ru/aspose.slides/islide/get_slide_comments/#icommentauthor) | Возвращает все комментарии к слайду, добавленные определённым автором. |
| [`write_as_emf(self, stream)`](/slides/python-net/ru/aspose.slides/islide/write_as_emf/#iorawiobase) | Сохраняет содержимое слайда в файл EMF. |
| [`remove(self)`](/slides/python-net/ru/aspose.slides/islide/remove/#) | Удаляет слайд из презентации. |
| [`reset(self)`](/slides/python-net/ru/aspose.slides/islide/reset/#) | Сбрасывает позицию, размер и форматирование каждой формы, у которой есть прототип на LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/islide/create_theme_effective/#) |  |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)