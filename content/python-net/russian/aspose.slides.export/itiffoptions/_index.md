---
title: ITiffOptions class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/itiffoptions/
---
## ITiffOptions класс

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате TIFF.

Тип ITiffOptions предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`image_size`](/slides/python-net/ru/aspose.slides.export/itiffoptions/image_size/) | Указывает размер генерируемого TIFF-изображения.<br/>            Значение по умолчанию — 0x0, что означает, что размеры генерируемого изображения будут вычислены на основе значения размера слайда презентации.<br/>            Чтение/запись **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/ru/aspose.slides.export/itiffoptions/dpi_x/) | Указывает горизонтальное разрешение в точках на дюйм.<br/>            Чтение/запись **int**. |
| [`dpi_y`](/slides/python-net/ru/aspose.slides.export/itiffoptions/dpi_y/) | Указывает вертикальное разрешение в точках на дюйм.<br/>            Чтение/запись **int**. |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/itiffoptions/show_hidden_slides/) | Указывает, должен ли генерируемый документ включать скрытые слайды или нет.<br/>            По умолчанию `false`. |
| [`compression_type`](/slides/python-net/ru/aspose.slides.export/itiffoptions/compression_type/) | Указывает тип сжатия.<br/>            Чтение/запись [`TiffCompressionTypes`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ru/aspose.slides.export/itiffoptions/pixel_format/) | Указывает формат пикселей для генерируемых изображений.<br/>            Чтение/запись [`ImagePixelFormat`](/slides/python-net/ru/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/itiffoptions/slides_layout_options/) | Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ru/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Указывает алгоритм преобразования цветного изображения в черно-белое.<br/>            Эта опция будет применяться только если [`ITiffOptions.compression_type`](/slides/python-net/ru/aspose.slides.export/itiffoptions/compression_type) <br/>            установлен в [`TiffCompressionTypes.CCITT4`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes/CCITT4) или [`TiffCompressionTypes.CCITT3`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Чтение/запись [`BlackWhiteConversionMode`](/slides/python-net/ru/aspose.slides.export/blackwhiteconversionmode).<br/>            По умолчанию [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ru/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/itiffoptions/ink_options/) | Предоставляет параметры, которые управляют внешним видом объектов Ink в экспортируемом документе.<br/>            Только чтение [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)