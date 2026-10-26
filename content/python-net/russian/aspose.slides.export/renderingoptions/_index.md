---
title: RenderingOptions class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/renderingoptions/
---
## Класс RenderingOptions

Предоставляет параметры, управляющие тем, как отображается презентация/слайд.

**Наследование:**[`RenderingOptions`](/slides/python-net/ru/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип RenderingOptions раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/renderingoptions/__init__/#) | Конструктор по умолчанию. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/renderingoptions/warning_callback/) | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или отменён.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/renderingoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/renderingoptions/default_regular_font/) | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/renderingoptions/gradient_style/) | Возвращает или устанавливает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/renderingoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`slides_layout_options`](/slides/python-net/ru/aspose.slides.export/renderingoptions/slides_layout_options/) | Получает или устанавливает режим размещения слайдов на странице при экспорте презентации [`ISlidesLayoutOptions`](/slides/python-net/ru/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ru/aspose.slides.export/renderingoptions/ink_options/) | Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортированном документе.<br/>            Только для чтения [`IInkOptions`](/slides/python-net/ru/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ru/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Получает или устанавливает значение, указывающее, будет ли текст визуализироваться без использования лигатур.<br/>            При установке в `true` лигатуры будут отключены в результирующем выводе. По умолчанию это свойство имеет значение `false`. |


### См. также
* класс [`RenderingOptions`](/slides/python-net/ru/aspose.slides.export/renderingoptions)
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)