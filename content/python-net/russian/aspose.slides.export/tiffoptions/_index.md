---
title: TiffOptions class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.export/tiffoptions/
---
## TiffOptions класс

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.

**Inheritance:**[`TiffOptions`](/slides/python-net/ru/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип TiffOptions раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/tiffoptions/__init__/#) | Конструктор по умолчанию. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/tiffoptions/warning_callback/) | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжаться или будет прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/tiffoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/tiffoptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/tiffoptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/tiffoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию **false**. |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/tiffoptions/ink_options/) | Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортируемом документе.<br/>            Только чтение [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/tiffoptions/show_hidden_slides/) | Указывает, должен ли сгенерированный документ включать скрытые слайды.<br/>            По умолчанию `false`. |
| [`image_size`](/slides/python-net/ru/aspose.slides.export/tiffoptions/image_size/) | Указывает размер генерируемого изображения TIFF.<br/>            Значение по умолчанию 0x0, что означает, что размеры сгенерированного изображения будут вычисляться на основе размера слайда презентации.<br/>            Чтение/запись **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/ru/aspose.slides.export/tiffoptions/dpi_x/) | Указывает горизонтальное разрешение в точках на дюйм.<br/>            Чтение/запись **int**. |
| [`dpi_y`](/slides/python-net/ru/aspose.slides.export/tiffoptions/dpi_y/) | Указывает вертикальное разрешение в точках на дюйм.<br/>            Чтение/запись **int**. |
| [`compression_type`](/slides/python-net/ru/aspose.slides.export/tiffoptions/compression_type/) | Указывает тип сжатия.<br/>            Чтение/запись [`TiffCompressionTypes`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ru/aspose.slides.export/tiffoptions/pixel_format/) | Указывает формат пикселей для генерируемых изображений.<br/>            Чтение/запись [`ImagePixelFormat`](/slides/python-net/ru/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/tiffoptions/slides_layout_options/) | Получает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ru/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Указывает алгоритм преобразования цветного изображения в черно-белое.<br/>            Эта опция будет применена только если [`TiffOptions.compression_type`](/slides/python-net/ru/aspose.slides.export/tiffoptions/compression_type) <br/>            установлена в [`TiffCompressionTypes.CCITT4`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes/CCITT4) или [`TiffCompressionTypes.CCITT3`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Чтение/запись [`BlackWhiteConversionMode`](/slides/python-net/ru/aspose.slides.export/blackwhiteconversionmode).<br/>            По умолчанию [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ru/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### См. также
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* класс [`TiffOptions`](/slides/python-net/ru/aspose.slides.export/tiffoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)