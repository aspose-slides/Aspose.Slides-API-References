---
title: SVGOptions class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/svgoptions/
---
## SVGOptions класс

Представляет параметры SVG.

**Наследование:**[`SVGOptions`](/slides/python-net/ru/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип SVGOptions предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/svgoptions/__init__/#) | Инициализирует новый экземпляр класса SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ru/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Инициализирует новый экземпляр класса SVGOptions, указывая объект контроллера встраивания ссылки. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/svgoptions/warning_callback/) | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/svgoptions/progress_callback/) | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/svgoptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/svgoptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/svgoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию **false**. |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/svgoptions/ink_options/) | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортированном документе.<br/>            Только чтение [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/ru/aspose.slides.export/svgoptions/use_frame_size/) | Определяет, будет ли текстовый кадр включён в область рендеринга.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию **false**. |
| [`use_frame_rotation`](/slides/python-net/ru/aspose.slides.export/svgoptions/use_frame_rotation/) | Определяет, выполнять ли указанную вращение фигуры при рендеринге.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию **true**. |
| [`vectorize_text`](/slides/python-net/ru/aspose.slides.export/svgoptions/vectorize_text/) | Определяет, будет ли текст на слайде сохранён как графика.<br/>            Чтение/запись **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ru/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Возвращает или задает нижний предел разрешения для растеризации метафайла.<br/>            Чтение/запись **int**. |
| [`disable_3d_text`](/slides/python-net/ru/aspose.slides.export/svgoptions/disable_3d_text/) | Определяет, отключён ли 3D-текст в SVG.<br/>            Чтение/запись **bool**. |
| [`disable_gradient_split`](/slides/python-net/ru/aspose.slides.export/svgoptions/disable_gradient_split/) | Отключает разбиение градиентов FromCornerX и FromCenter.<br/>            Чтение/запись **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ru/aspose.slides.export/svgoptions/disable_line_end_cropping/) | В SVG 1.1 отсутствует возможность задавать отступы для маркеров.<br/>            Движок записи Aspose.Slides SVG имеет обходное решение этой проблемы:<br/>            он обрезает конец линии со стрелкой, чтобы линия не перекрывала маркеры.<br/>            Эта опция отключает такое поведение.<br/>            Чтение/запись **bool**. |
| [`default`](/slides/python-net/ru/aspose.slides.export/svgoptions/default/) | Возвращает настройки по умолчанию.<br/>            Только чтение [`SVGOptions`](/slides/python-net/ru/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/ru/aspose.slides.export/svgoptions/simple/) | Возвращает настройки для простейшей и наименьшей генерации SVG-файла.<br/>            Только чтение [`SVGOptions`](/slides/python-net/ru/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/ru/aspose.slides.export/svgoptions/wysiwyg/) | Возвращает настройки для наиболее точной генерации SVG-файла.<br/>            Только чтение [`SVGOptions`](/slides/python-net/ru/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/ru/aspose.slides.export/svgoptions/jpeg_quality/) | Определяет качество кодирования JPEG.<br/>            Чтение/запись **int**. |
| [`shape_formatting_controller`](/slides/python-net/ru/aspose.slides.export/svgoptions/shape_formatting_controller/) | Возвращает и задает интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур.<br/>            Чтение/запись [`ISvgShapeFormattingController`](/slides/python-net/ru/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ru/aspose.slides.export/svgoptions/pictures_compression/) | Представляет уровень сжатия изображений |
| [`delete_pictures_cropped_areas`](/slides/python-net/ru/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Булевый флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные<br/>            части будут удалены, если false — они будут сериализованы в документе (что может привести к<br/>            большему размеру файла) |
| [`external_fonts_handling`](/slides/python-net/ru/aspose.slides.export/svgoptions/external_fonts_handling/) | Определяет способ обработки внешне загруженных шрифтов.<br/>            Чтение/запись [`SvgExternalFontsHandling`](/slides/python-net/ru/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/ru/aspose.slides.export/svgoptions/disable_font_ligatures/) | Получает или задает значение, указывающее, отображается ли текст без использования лигатур.<br/>            При установке в `true` лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение `false`. |


### См. также
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* класс [`SVGOptions`](/slides/python-net/ru/aspose.slides.export/svgoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)