---
title: PptOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.export/pptoptions/
---
## PptOptions класс

Предоставляет параметры, контролирующие, как презентация сохраняется в формате PPT.

**Inheritance:**[`PptOptions`](/slides/python-net/ru/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип PptOptions предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/pptoptions/__init__/#) |  |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/pptoptions/warning_callback/) | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/pptoptions/progress_callback/) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/pptoptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/pptoptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/pptoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`root_directory_clsid`](/slides/python-net/ru/aspose.slides.export/pptoptions/root_directory_clsid/) | Представляет GUID класса объекта (CLSID), хранящийся в записи корневого каталога. Может использоваться для COM<br/>            активации приложения документа.<br/>            Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'. |

### См. также
* класс [`PptOptions`](/slides/python-net/ru/aspose.slides.export/pptoptions)
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)