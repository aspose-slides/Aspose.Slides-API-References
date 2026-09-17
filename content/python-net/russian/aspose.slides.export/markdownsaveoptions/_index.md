---
title: MarkdownSaveOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions класс

Представляет параметры, контролирующие, как презентация должна сохраняться в markdown.

**Наследование:**[`MarkdownSaveOptions`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип MarkdownSaveOptions предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/__init__/#) | Конструктор. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/warning_callback/) | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`export_type`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/export_type/) | Указывает спецификацию markdown для преобразования презентации.<br/>            По умолчанию `TextOnly`. |
| [`base_path`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/base_path/) | Указывает базовый путь, где будет сохранён документ с ресурсами.<br/>            По умолчанию — текущий каталог приложения. |
| [`images_save_folder_name`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Указывает имя папки для сохранения изображений.<br/>            По умолчанию `Images`. |
| [`new_line_type`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/new_line_type/) | Указывает, должны ли сгенерированные документы иметь символы новой строки \\r (Macintosh), \\n (Unix) или \\r\\n (Windows).<br/>            По умолчанию `Unix`. |
| [`show_comments`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/show_comments/) | Указывает, должны ли сгенерированные документы показывать комментарии.<br/>            По умолчанию `false`. |
| [`show_hidden_slides`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Указывает, должны ли сгенерированные документы включать скрытые слайды.<br/>            По умолчанию `false`. |
| [`show_slide_number`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Указывает, должны ли сгенерированные документы показывать номер каждого слайда.<br/>            По умолчанию `false`. |
| [`flavor`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/flavor/) | Указывает спецификацию markdown для преобразования презентации.<br/>            По умолчанию `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Возвращает или задает строку формата, используемую для заголовков номеров слайдов в выводе Markdown.<br/>            Формат должен включать заполнитель \"{0}\", который будет заменён индексом слайда при экспорте.<br/>            Пример: \"# Slide {0}\" будет преобразовано в \"# Slide 1\", \"# Slide 2\" и т.д. |
| [`handle_repeated_spaces`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Если установлено `true`, удаляет пустые строки или строки, содержащие только пробелы, из окончательного вывода Markdown.<br/>            По умолчанию `false`. |


### Смотрите также
* класс [`MarkdownSaveOptions`](/slides/python-net/ru/aspose.slides.export/markdownsaveoptions)
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)