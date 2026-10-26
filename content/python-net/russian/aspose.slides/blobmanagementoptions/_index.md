---
title: BlobManagementOptions class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions класс

Представляет параметры, которые могут использоваться для управления правилами обработки BLOB и другими настройками BLOB.

Тип BlobManagementOptions раскрывает следующие члены:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/blobmanagementoptions/__init__/#) | Создаёт новые параметры управления BLOB по умолчанию. |

## Свойства

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ru/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем исходного файла <br/>            или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает <br/>            улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) <br/>            не может быть изменён в течение срока жизни экземпляра Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/ru/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно <br/>            уменьшает потребление памяти, но требует разрешений на создание файлов.<br/>            Все файлы будут удалены после завершения работы с презентацией. |
| [`temp_files_root_path`](/slides/python-net/ru/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться системный временный каталог. <br/>            Процесс-хост должен иметь разрешения на <br/>            создание файлов и папок в этом месте. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ru/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB<br/>            загружаются в память; только когда достигается этот предел, используются альтернативные механизмы (например, временные<br/>            файлы). Хранение BLOB в памяти максимизирует производительность, но может привести к высокому использованию памяти. Используйте<br/>            это свойство, чтобы адаптировать поведение к вашей среде или требованиям. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)