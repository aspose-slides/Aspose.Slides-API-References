---
title: ITiffOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/itiffoptions/
---
## ITiffOptions класс

Предоставляет параметры, управляющие тем, как презентация сохраняется в формате TIFF.

Тип ITiffOptions раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/ru/aspose.slides.export/itiffoptions/image_size/) | Указывает размер генерируемого TIFF-изображения.<br/>            Значение по умолчанию 0x0, что означает, что размеры генерируемого изображения будут вычислены на основе размера слайда презентации.<br/>            Чтение/запись [`Size`](/slides/python-net/ru/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/ru/aspose.slides.export/itiffoptions/dpi_x/) | Указывает горизонтальное разрешение в точках на дюйм.<br/>            Чтение/запись **int**. |
| [`dpi_y`](/slides/python-net/ru/aspose.slides.export/itiffoptions/dpi_y/) | Указывает вертикальное разрешение в точках на дюйм.<br/>            Чтение/запись **int**. |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/itiffoptions/show_hidden_slides/) | Указывает, следует ли включать скрытые слайды в генерируемый документ или нет.<br/>            Значение по умолчанию `false`. |
| [`compression_type`](/slides/python-net/ru/aspose.slides.export/itiffoptions/compression_type/) | Указывает тип сжатия.<br/>            Чтение/запись [`TiffCompressionTypes`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ru/aspose.slides.export/itiffoptions/pixel_format/) | Указывает формат пикселей для генерируемых изображений.<br/>            Чтение/запись [`ImagePixelFormat`](/slides/python-net/ru/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/itiffoptions/slides_layout_options/) | Получает или задает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ru/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Указывает алгоритм преобразования цветного изображения в черно-белое.<br/>            Эта опция применяется только если [`ITiffOptions.compression_type`](/slides/python-net/ru/aspose.slides.export/itiffoptions/compression_type) <br/>            установлен в [`TiffCompressionTypes.CCITT4`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes/CCITT4) или [`TiffCompressionTypes.CCITT3`](/slides/python-net/ru/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Чтение/запись [`BlackWhiteConversionMode`](/slides/python-net/ru/aspose.slides.export/blackwhiteconversionmode).<br/>            Значение по умолчанию [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ru/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/itiffoptions/ink_options/) | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе.<br/>            Только чтение [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Смотрите также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)