---
title: LoadOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/loadoptions/
---
## LoadOptions класс

Позволяет указывать дополнительные параметры (например, формат или шрифт по умолчанию) при загрузке презентации.

Тип LoadOptions предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/loadoptions/__init__/#) | Создает новые параметры загрузки по умолчанию. |
| [`__init__(self, load_format)`](/slides/python-net/ru/aspose.slides/loadoptions/__init__/#loadformat) | Создает новые параметры загрузки. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`load_format`](/slides/python-net/ru/aspose.slides/loadoptions/load_format/) | Возвращает или задает формат презентации для загрузки.<br/>            Чтение/запись [`LoadFormat`](/slides/python-net/ru/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides/loadoptions/default_regular_font/) | Возвращает или задает обычный шрифт, используемый, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`default_symbol_font`](/slides/python-net/ru/aspose.slides/loadoptions/default_symbol_font/) | Возвращает или задает шрифт Symbol, используемый, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`default_asian_font`](/slides/python-net/ru/aspose.slides/loadoptions/default_asian_font/) | Возвращает или задает азиатский шрифт, используемый, если исходный шрифт не найден.<br/>            Чтение/запись **str**. |
| [`password`](/slides/python-net/ru/aspose.slides/loadoptions/password/) | Получает или задает пароль.<br/>            Чтение/запись **str**. |
| [`only_load_document_properties`](/slides/python-net/ru/aspose.slides/loadoptions/only_load_document_properties/) | Это свойство имеет смысл, если файл презентации защищён паролем.<br/>            Значение true означает, что должны быть загружены только свойства документа из зашифрованного <br/>            файла презентации, а пароль игнорируется.<br/>            Значение false означает, что вся зашифрованная презентация должна быть загружена с использованием правильного <br/>            пароля.<br/>            Если презентация не зашифрована, значение свойства всегда игнорируется.<br/>            Если свойства документа зашифрованного файла не публичны и значение свойства равно true, то<br/>            свойства документа не могут быть загружены, и будет выброшено исключение.<br/>            Чтение/запись **bool**. |
| [`warning_callback`](/slides/python-net/ru/aspose.slides/loadoptions/warning_callback/) | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки <br/>            продолжаться или будет прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ru/aspose.slides/loadoptions/blob_management_options/) | Представляет параметры, которые могут использоваться для управления поведением обработки Binary Large Objects (BLOBs),<br/>            таких как использование временных файлов или максимальное количество байт BLOBs в памяти. Эти параметры предназначены для настройки<br/>            наилучшего соотношения производительность/потребление памяти для конкретной среды или требований.<br/>            Binary Large Object (BLOB) — это бинарные данные, хранящиеся как единый объект, т.е. BLOB может быть<br/>            аудио, видео или сама презентация. |
| [`document_level_font_sources`](/slides/python-net/ru/aspose.slides/loadoptions/document_level_font_sources/) | Указывает источники внешних шрифтов, используемых презентацией.<br/>            Эти шрифты доступны презентации на протяжении всего её жизненного цикла и не совместно используются другими презентациями |
| [`interruption_token`](/slides/python-net/ru/aspose.slides/loadoptions/interruption_token/) | Токен для отслеживания запросов на прерывание.<br/>            <br/>            Этот токен управляет полной жизненной циклом экземпляра [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). Любая длительная операция, такая как загрузка <br/>            или сохранение презентации, будет прервана вызовом метода [`InterruptionTokenSource.interrupt`](/slides/python-net/ru/aspose.slides/interruptiontokensource/interrupt) у <br/>            [`InterruptionTokenSource`](/slides/python-net/ru/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/ru/aspose.slides/loadoptions/resource_loading_callback/) | Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов.<br/>            Чтение/запись [`IResourceLoadingCallback`](/slides/python-net/ru/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ru/aspose.slides/loadoptions/spreadsheet_options/) | Получает параметры для электронных таблиц. Например, эти параметры влияют на вычисление формул для диаграмм. |
| [`default_text_language`](/slides/python-net/ru/aspose.slides/loadoptions/default_text_language/) | Возвращает или задает язык по умолчанию для текста презентации.<br/>            Чтение/запись **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ru/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Определяет, будет ли Aspose.Slides удалять все встроенные бинарные объекты при загрузке презентации.<br/>            <br/>Типы встроенных бинарных объектов:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/ru/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/ru/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Чтение/запись **bool**. |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)