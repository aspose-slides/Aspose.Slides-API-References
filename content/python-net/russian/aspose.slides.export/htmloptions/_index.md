---
title: HtmlOptions class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/htmloptions/
---
## HtmlOptions класс

Представляет параметры экспорта HTML.

**Inheritance:**[`HtmlOptions`](/slides/python-net/ru/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип HtmlOptions открывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ru/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Creates a new HtmlOptions object specifiing callback. |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/htmloptions/__init__/#) | Creates a new HtmlOptions object for saving into single HTML file. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/htmloptions/warning_callback/) | Возвращает или задает объект, который получает предупреждения и решает, продолжать ли процесс загрузки или прервать его.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/htmloptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/htmloptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/htmloptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/htmloptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/htmloptions/slides_layout_options/) | Возвращает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/htmloptions/ink_options/) | Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортированном документе.<br/>            Только для чтения [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/htmloptions/show_hidden_slides/) | Указывает, следует ли включать скрытые слайды в сгенерированный документ.<br/>            По умолчанию `false`. |
| [`html_formatter`](/slides/python-net/ru/aspose.slides.export/htmloptions/html_formatter/) | Возвращает или задает шаблон HTML.<br/>            Чтение/запись [`IHtmlFormatter`](/slides/python-net/ru/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/ru/aspose.slides.export/htmloptions/disable_font_ligatures/) | Возвращает или задает значение, указывающее, отображать ли текст без использования лигатур.<br/>            При установке в `true` лигатуры будут отключены в выводе. По умолчанию это свойство установлено в `false`. |
| [`slide_image_format`](/slides/python-net/ru/aspose.slides.export/htmloptions/slide_image_format/) | Возвращает или задает параметры формата изображений слайдов.<br/>            Чтение/запись [`ISlideImageFormat`](/slides/python-net/ru/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/ru/aspose.slides.export/htmloptions/jpeg_quality/) | Возвращает или задает значение, определяющее качество JPEG-изображений в документе PDF.<br/>            Чтение/запись **int**. |
| [`pictures_compression`](/slides/python-net/ru/aspose.slides.export/htmloptions/pictures_compression/) | Представляет уровень сжатия изображений |
| [`delete_pictures_cropped_areas`](/slides/python-net/ru/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Булевый флаг, указывающий, остаются ли обрезанные части частью документа. Если `true`, обрезанные<br/>            части будут удалены, если `false` — они будут сериализованы в документе (что может привести к<br/>            большему файлу) |
| [`svg_responsive_layout`](/slides/python-net/ru/aspose.slides.export/htmloptions/svg_responsive_layout/) | `true`, чтобы исключить атрибуты width и height из контейнера svg — это сделает макет адаптивным. `false` — иначе.<br/>            Чтение/запись **bool**. |


### См. также
* класс [`HtmlOptions`](/slides/python-net/ru/aspose.slides.export/htmloptions)
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)