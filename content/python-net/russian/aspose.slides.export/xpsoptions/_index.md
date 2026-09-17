---
title: XpsOptions class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.export/xpsoptions/
---
## XpsOptions класс

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате XPS.

**Наследование:**[`XpsOptions`](/slides/python-net/ru/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип XpsOptions раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/xpsoptions/__init__/#) | Конструктор по умолчанию. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/xpsoptions/warning_callback/) | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/xpsoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            Смотрите [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/xpsoptions/default_regular_font/) | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/xpsoptions/gradient_style/) | Возвращает или устанавливает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/xpsoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию **false** . |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/xpsoptions/show_hidden_slides/) | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет.<br/>            По умолчанию `false`. |
| [`save_metafiles_as_png`](/slides/python-net/ru/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | True, чтобы конвертировать все метафайлы, используемые в презентации, в изображения PNG.<br/>            Чтение/запись **bool**. |
| [`draw_slides_frame`](/slides/python-net/ru/aspose.slides.export/xpsoptions/draw_slides_frame/) | True, чтобы рисовать черную рамку вокруг каждого слайда.<br/>            Чтение/запись **bool**. |


### См. также
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* класс [`XpsOptions`](/slides/python-net/ru/aspose.slides.export/xpsoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)