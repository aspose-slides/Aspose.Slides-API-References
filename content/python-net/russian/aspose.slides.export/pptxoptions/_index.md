---
title: PptxOptions class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/pptxoptions/
---
## PptxOptions класс

Представляет параметры для сохранения презентаций OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Наследование:**[`PptxOptions`](/slides/python-net/ru/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)

Тип PptxOptions предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.export/pptxoptions/__init__/#) | Создает новый экземпляр PptxOptions |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`warning_callback`](/slides/python-net/ru/aspose.slides.export/pptxoptions/warning_callback/) | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ru/aspose.slides.export/pptxoptions/progress_callback/) | Представляет объект обратного вызова для обновлений прогресса сохранения в процентах.<br/>            См. [`IProgressCallback`](/slides/python-net/ru/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides.export/pptxoptions/default_regular_font/) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`gradient_style`](/slides/python-net/ru/aspose.slides.export/pptxoptions/gradient_style/) | Возвращает или задает визуальный стиль градиента.<br/>            Чтение/запись [`GradientStyle`](/slides/python-net/ru/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ru/aspose.slides.export/pptxoptions/skip_java_script_links/) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации.<br/>            Чтение/запись **bool**. Значение по умолчанию — **false**. |
| [`conformance`](/slides/python-net/ru/aspose.slides.export/pptxoptions/conformance/) | Указывает класс соответствия, которому соответствует документ Presentation.<br/>            Значение по умолчанию — [`Conformance.ECMA_376_2006`](/slides/python-net/ru/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/ru/aspose.slides.export/pptxoptions/zip_64_mode/) | Указывает, используется ли формат ZIP64 для документа Presentation.<br/>            Значение по умолчанию — [`Zip64Mode.IF_NECESSARY`](/slides/python-net/ru/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/ru/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Указывает, будет ли обновляться миниатюра презентации.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию — **true**. |
| [`compression_level`](/slides/python-net/ru/aspose.slides.export/pptxoptions/compression_level/) | Указывает уровень сжатия, используемый при сохранении документа презентации.<br/>            Значение по умолчанию — [`CompressionLevel.LEVEL6`](/slides/python-net/ru/aspose.slides.export/compressionlevel/LEVEL6). |

### См. также
* класс [`PptxOptions`](/slides/python-net/ru/aspose.slides.export/pptxoptions)
* класс [`SaveOptions`](/slides/python-net/ru/aspose.slides.export/saveoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)