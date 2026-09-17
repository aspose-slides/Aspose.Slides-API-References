---
title: IPdfOptions class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/ipdfoptions/
---
## IPdfOptions класс

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате Pdf.

Тип IPdfOptions раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`text_compression`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/text_compression/) | Указывает тип сжатия, который будет использоваться для всего текстового содержимого документа.<br/>            Чтение/запись [`PdfTextCompression`](/slides/python-net/ru/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения.<br/>            Если установлено **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к меньшему размеру итогового PDF-документа.<br/>            Выбор оптимального коэффициента сжатия изображения требует значительных вычислительных ресурсов и дополнительного объёма ОЗУ, и по умолчанию эта опция **bool**.false. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | True, чтобы встраивать TrueType-шрифты для символов ASCII 32-127.<br/>            Шрифты для символов с кодами выше 127 всегда встраиваются.<br/>            Чтение/запись **bool**. |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Указывает, следует ли включать скрытые слайды в генерируемый документ.<br/>            По умолчанию `false`. |
| [`additional_common_font_families`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Возвращает или задаёт массив пользовательских названий семейств шрифтов, которые Aspose.Slides следует рассматривать как общие.<br/>            Чтение/запись **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество.<br/>            Чтение/запись **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Указывает, следует ли растировать текст как растровое изображение и сохранять его в PDF, если шрифт не поддерживает полужирное начертание.<br/>            Такой подход может улучшить качество текста в получаемом PDF для некоторых шрифтов.<br/>            Чтение/запись **bool**. |
| [`jpeg_quality`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/jpeg_quality/) | Возвращает или задаёт значение, определяющее качество JPEG-изображений внутри PDF-документа.<br/>            Чтение/запись **int**. |
| [`compliance`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/compliance/) | Желаемый уровень соответствия для генерируемого PDF-документа.<br/>            Чтение/запись [`PdfCompliance`](/slides/python-net/ru/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/password/) | Установка пароля пользователя для защиты PDF-документа.<br/>            Чтение/запись **str**. |
| [`access_permissions`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/access_permissions/) | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем.<br/>            См. [`PdfAccessPermissions`](/slides/python-net/ru/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | True, чтобы конвертировать все метафайлы, использованные в презентации, в PNG-изображения.<br/>            Чтение/запись **bool**. |
| [`sufficient_resolution`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Возвращает или задаёт значение, определяющее разрешение изображений внутри PDF-документа.<br/>            <br/>Свойство влияет на размер файла, время экспорта и качество изображения.<br/><br/><br/>Значение по умолчанию — **96**.<br/><br/><br/>            Чтение/запись **float**. |
| [`draw_slides_frame`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/draw_slides_frame/) | True, чтобы рисовать чёрную рамку вокруг каждого слайда.<br/>            Чтение/запись **bool**. |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/slides_layout_options/) | Получает или задаёт режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/image_transparent_color/) | Получает или задаёт прозрачный цвет изображения. |
| [`apply_image_transparent`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Применяет указанный прозрачный цвет к изображению, если `true`. |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/ink_options/) | Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортируемом документе.<br/>            Только для чтения [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/include_ole_data/) | True, чтобы конвертировать все OLE-данные из презентации во встраиваемые файлы в получаемом PDF.<br/>            Чтение/запись **bool**. |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### См. также
* module [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)