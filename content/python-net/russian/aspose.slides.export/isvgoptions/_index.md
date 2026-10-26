---
title: ISVGOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/isvgoptions/
---
## ISVGOptions класс

Представляет параметры SVG.

Тип ISVGOptions раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`vectorize_text`](/slides/python-net/ru/aspose.slides.export/isvgoptions/vectorize_text/) | Определяет, будет ли текст на слайде сохраняться как графика.<br/>            Чтение/запись **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ru/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Возвращает или задает нижний предел разрешения для растеризации метафайла.<br/>            Чтение/запись **int**. |
| [`disable_3d_text`](/slides/python-net/ru/aspose.slides.export/isvgoptions/disable_3d_text/) | Определяет, отключён ли 3D-текст в SVG.<br/>            Чтение/запись **bool**. |
| [`disable_gradient_split`](/slides/python-net/ru/aspose.slides.export/isvgoptions/disable_gradient_split/) | Отключает разделение градиентов FromCornerX и FromCenter.<br/>            Чтение/запись **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ru/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | В SVG 1.1 отсутствует возможность задавать отступы для маркеров.<br/>            У движка записи SVG Aspose.Slides есть обходное решение этой проблемы:<br/>            он обрезает конец линии со стрелкой, поэтому линия не перекрывает маркеры.<br/>            Эта опция отключает такое поведение.<br/>            Чтение/запись **bool**. |
| [`jpeg_quality`](/slides/python-net/ru/aspose.slides.export/isvgoptions/jpeg_quality/) | Определяет качество кодирования JPEG.<br/>            Чтение/запись **int**. |
| [`shape_formatting_controller`](/slides/python-net/ru/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Возвращает и задает интерфейс обратного вызова, который позволяет пользователю управлять преобразованием фигур.<br/>            Чтение/запись [`ISvgShapeFormattingController`](/slides/python-net/ru/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ru/aspose.slides.export/isvgoptions/pictures_compression/) | Представляет уровень сжатия изображений<br/>            Чтение/запись [`ISVGOptions.pictures_compression`](/slides/python-net/ru/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/ru/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Булевский флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные <br/>            части будут удалены, если false — они будут сериализованы в документе (что может привести к <br/>            большему файлу)<br/>            Чтение/запись **bool**. |
| [`use_frame_size`](/slides/python-net/ru/aspose.slides.export/isvgoptions/use_frame_size/) | Определяет, будет ли текстовый кадр включён в область визуализации или нет.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию — false. |
| [`use_frame_rotation`](/slides/python-net/ru/aspose.slides.export/isvgoptions/use_frame_rotation/) | Определяет, выполнять ли указанное вращение фигуры при визуализации.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию — true. |
| [`external_fonts_handling`](/slides/python-net/ru/aspose.slides.export/isvgoptions/external_fonts_handling/) | Определяет способ обработки внешне загруженных шрифтов.<br/>            Чтение/запись [`SvgExternalFontsHandling`](/slides/python-net/ru/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/isvgoptions/ink_options/) | Предоставляет параметры, управляющие внешним видом Ink-объектов в экспортированном документе.<br/>            Только для чтения [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ru/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Получает или задаёт значение, указывающее, отображается ли текст без использования лигатур.<br/>            При установке в `true` лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение `false`. |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)