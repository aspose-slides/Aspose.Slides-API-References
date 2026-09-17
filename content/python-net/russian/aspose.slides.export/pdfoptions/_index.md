---
title: PdfOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/pdfoptions/
---
## PdfOptions класс

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.

**Inheritance:**[`PdfOptions`](/slides/python-net/ru/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип PdfOptions раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/pdfoptions/__init__/#) | Конструктор по умолчанию. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/pdfoptions/warning_callback/) | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/pdfoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/pdfoptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/pdfoptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/pdfoptions/skip_java_script_links/) | Указывает, следует ли пропустить гиперссылки с вызовами JavaScript при сохранении презентации. <br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/pdfoptions/slides_layout_options/) | Возвращает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/pdfoptions/ink_options/) | Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортированном документе.<br/>            Только для чтения [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/pdfoptions/show_hidden_slides/) | Указывает, следует ли включать скрытые слайды в сгенерированный документ.<br/>            По умолчанию `false`. |
| [`text_compression`](/slides/python-net/ru/aspose.slides.export/pdfoptions/text_compression/) | Указывает тип сжатия, используемый для всего текстового содержимого в документе.<br/>            Чтение/запись [`PdfTextCompression`](/slides/python-net/ru/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ru/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения <br/>            автоматически. Если установить **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия <br/>            , что приведёт к уменьшенному размеру результирующего PDF-документа. <br/>            Выбор лучшего коэффициента сжатия изображения требует значительных вычислительных ресурсов и <br/>            дополнительного объёма ОЗУ, при этом параметр по умолчанию **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ru/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Определяет, будет ли Aspose.Slides встраивать общие шрифты для текста ASCII (диапазон кодов 33..127).<br/>            Шрифты для кодов символов больше 127 всегда встраиваются.<br/>            Список общих шрифтов включает базовые 14 шрифтов PDF и дополнительные пользовательские шрифты.<br/>            Чтение/запись **bool**. |
| [`additional_common_font_families`](/slides/python-net/ru/aspose.slides.export/pdfoptions/additional_common_font_families/) | Возвращает или задает массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими.<br/>            Чтение/запись **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ru/aspose.slides.export/pdfoptions/embed_full_fonts/) | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество.<br/>            Чтение/запись **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ru/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Указывает, следует ли растеризовать текст как растровое изображение и сохранить в PDF, если шрифт не поддерживает полужирное начертание.<br/>            Этот подход может повысить качество текста в результирующем PDF для некоторых шрифтов.<br/>            Чтение/запись **bool**. |
| [`jpeg_quality`](/slides/python-net/ru/aspose.slides.export/pdfoptions/jpeg_quality/) | Возвращает или задает значение, определяющее качество JPEG-изображений в PDF-документе.<br/>            Чтение/запись **int**. |
| [`compliance`](/slides/python-net/ru/aspose.slides.export/pdfoptions/compliance/) | Желаемый уровень соответствия для генерируемого PDF-документа.<br/>            Чтение/запись [`PdfCompliance`](/slides/python-net/ru/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ru/aspose.slides.export/pdfoptions/password/) | Установка пользовательского пароля для защиты PDF-документа.<br/>            Чтение/запись **str**. |
| [`access_permissions`](/slides/python-net/ru/aspose.slides.export/pdfoptions/access_permissions/) | Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа<br/>            с пользовательским доступом. См. [`PdfAccessPermissions`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/ru/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Истина, если нужно преобразовать все метафайлы, используемые в презентации, в изображения PNG.<br/>            Чтение/запись **bool**. |
| [`sufficient_resolution`](/slides/python-net/ru/aspose.slides.export/pdfoptions/sufficient_resolution/) | Возвращает или задает значение, определяющее разрешение изображений в PDF-документе.<br/>            <br/>Свойство влияет на размер файла, время экспорта и качество изображения.<br/><br/><br/>Значение по умолчанию — **96**.<br/><br/><br/>            Чтение/запись **float**. |
| [`draw_slides_frame`](/slides/python-net/ru/aspose.slides.export/pdfoptions/draw_slides_frame/) | Истина, если нужно рисовать чёрную рамку вокруг каждого слайда.<br/>             Чтение/запись **bool**. |
| [`image_transparent_color`](/slides/python-net/ru/aspose.slides.export/pdfoptions/image_transparent_color/) | Возвращает или задает прозрачный цвет изображения. |
| [`apply_image_transparent`](/slides/python-net/ru/aspose.slides.export/pdfoptions/apply_image_transparent/) | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [`include_ole_data`](/slides/python-net/ru/aspose.slides.export/pdfoptions/include_ole_data/) | Истина, если нужно преобразовать все OLE-данные из презентации во встроенные файлы в результирующем PDF.<br/>            Чтение/запись **bool**. |

### Смотрите также
* класс [`PdfOptions`](/slides/python-net/ru/aspose.slides.export/pdfoptions)
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)