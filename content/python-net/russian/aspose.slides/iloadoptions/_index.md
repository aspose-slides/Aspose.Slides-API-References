---
title: ILoadOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iloadoptions/
---
## ILoadOptions класс

Позволяет указать дополнительные параметры (например, формат или шрифт по умолчанию) при загрузке презентации.

Тип ILoadOptions раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`load_format`](/slides/python-net/ru/aspose.slides/iloadoptions/load_format/) | Возвращает или задает формат презентации для загрузки.<br/>            Чтение/запись [`LoadFormat`](/slides/python-net/ru/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ru/aspose.slides/iloadoptions/default_regular_font/) | Возвращает или задает обычный шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`default_symbol_font`](/slides/python-net/ru/aspose.slides/iloadoptions/default_symbol_font/) | Возвращает или задает шрифт Symbol, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`default_asian_font`](/slides/python-net/ru/aspose.slides/iloadoptions/default_asian_font/) | Возвращает или задает азиатский шрифт, используемый в случае, если исходный шрифт не найден.<br/>            Чтение-запись **str**. |
| [`password`](/slides/python-net/ru/aspose.slides/iloadoptions/password/) | Возвращает или задает пароль.<br/>            Чтение-запись **str**. |
| [`only_load_document_properties`](/slides/python-net/ru/aspose.slides/iloadoptions/only_load_document_properties/) | Этот параметр имеет смысл, если файл презентации защищён паролем.<br/>            Значение true означает, что из зашифрованного файла презентации должны быть загружены только свойства документа, а пароль игнорируется.<br/>            Значение false означает, что вся зашифрованная презентация должна быть загружена с использованием правильного пароля.<br/>            Если презентация не зашифрована, значение параметра всегда игнорируется.<br/>            Если свойства документа зашифрованного файла не являются публичными и значение параметра равно true, то свойства документа загрузить нельзя, будет выброшено исключение.<br/>            Чтение-запись **bool**. |
| [`warning_callback`](/slides/python-net/ru/aspose.slides/iloadoptions/warning_callback/) | Возвращает или задает объект, получающий предупреждения и определяющий, будет ли процесс загрузки продолжен или прерван.<br/>            Чтение/запись [`IWarningCallback`](/slides/python-net/ru/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ru/aspose.slides/iloadoptions/blob_management_options/) | Представляет параметры, которые могут использоваться для управления поведением обработки Binary Large Objects (BLOBs),<br/>            например, использованием временных файлов или максимальным объёмом BLOBs в памяти. Эти параметры предназначены для настройки<br/>            лучшего соотношения производительности и потребления памяти для конкретной среды или требований.<br/>            Binary Large Object (BLOB) — это бинарные данные, хранящиеся как единый объект; то есть BLOB может быть<br/>            аудио, видео или самой презентацией. |
| [`document_level_font_sources`](/slides/python-net/ru/aspose.slides/iloadoptions/document_level_font_sources/) | Указывает источники внешних шрифтов, используемых презентацией.<br/>            Эти шрифты доступны презентации в течение всего её жизненного цикла и не используются другими презентациями |
| [`interruption_token`](/slides/python-net/ru/aspose.slides/iloadoptions/interruption_token/) | Токен для отслеживания запросов на прерывание.<br/>            <br/>            Этот токен управляет всей длительностью экземпляра [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана вызовом метода [`IInterruptionTokenSource.interrupt`](/slides/python-net/ru/aspose.slides/iinterruptiontokensource/interrupt) у [`IInterruptionTokenSource`](/slides/python-net/ru/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/ru/aspose.slides/iloadoptions/resource_loading_callback/) | Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов.<br/>            Чтение/запись [`IResourceLoadingCallback`](/slides/python-net/ru/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ru/aspose.slides/iloadoptions/spreadsheet_options/) | Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц. |
| [`default_text_language`](/slides/python-net/ru/aspose.slides/iloadoptions/default_text_language/) | Возвращает или задает язык по умолчанию для текста презентации.<br/>             Чтение/запись **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ru/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Определяет, будет ли Aspose.Slides удалять все встроенные бинарные объекты при загрузке презентации.<br/>            <br/>Типы встроенных бинарных объектов:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/ru/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/ru/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Чтение/запись **bool**. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)