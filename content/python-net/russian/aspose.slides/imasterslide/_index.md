---
title: IMasterSlide class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/imasterslide/
---
## IMasterSlide класс

Представляет главный слайд в презентации.

Тип IMasterSlide предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ru/aspose.slides/imasterslide/header_footer_manager/) | Возвращает менеджер HeaderFooter мастера слайда.<br/>            Только для чтения [`IMasterSlideHeaderFooterManager`](/slides/python-net/ru/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ru/aspose.slides/imasterslide/title_style/) | Возвращает стиль текста заголовка.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ru/aspose.slides/imasterslide/body_style/) | Возвращает стиль основного текста.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ru/aspose.slides/imasterslide/other_style/) | Возвращает стиль другого текста.<br/>            Только для чтения [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ru/aspose.slides/imasterslide/layout_slides/) | Возвращает коллекцию дочерних макетных слайдов для этого мастера слайда.<br/>            Только для чтения [`IMasterLayoutSlideCollection`](/slides/python-net/ru/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ru/aspose.slides/imasterslide/preserve/) | Определяет, будет ли соответствующий мастер удалён, когда все <br/>            слайды, которые следуют за этим мастером, удалены.<br/>            Примечание: Aspose.Slides никогда не будет удалять неиспользуемый мастер самостоятельно, <br/>            чтобы действительно удалить неиспользуемые мастеры, вызовите **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Чтение/запись **bool**. |
| [`has_depending_slides`](/slides/python-net/ru/aspose.slides/imasterslide/has_depending_slides/) | Возвращает true, если существует хотя бы один слайд, зависящий от этого мастера слайда.<br/>            Только для чтения **bool**. |
| [`drawing_guides`](/slides/python-net/ru/aspose.slides/imasterslide/drawing_guides/) | Возвращает коллекцию направляющих рисования для мастера слайда.<br/>            Только для чтения [`IDrawingGuidesCollection`](/slides/python-net/ru/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/ru/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/ru/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/ru/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/ru/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ru/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/ru/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ru/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ru/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ru/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ru/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ru/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ru/aspose.slides/imasterslide/theme_manager/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ru/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Создаёт новый мастер-слайд на основе текущего, применяя к нему внешнюю тему <br/>            и применяет созданный мастер-слайд ко всем зависимым слайдам. |
| [`get_depending_slides(self)`](/slides/python-net/ru/aspose.slides/imasterslide/get_depending_slides/#) | Возвращает массив со всеми слайдами, которые зависят от этого мастер-слайда. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ru/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ru/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ru/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)