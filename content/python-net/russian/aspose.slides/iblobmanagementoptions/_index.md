---
title: IBlobManagementOptions class
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions класс

Binary Large Object (BLOB) — это двоичные данные, хранящиеся как единый объект, то есть BLOB может быть аудио, видео или самой презентацией. Для оптимизации потребления памяти при работе с BLOB используют различные техники — как с уже сохранёнными в презентации BLOB, так и добавляемыми позже программно. С помощью [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions) вы можете изменить различные аспекты поведения при работе с BLOB для времени жизни экземпляра [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation).

Тип IBlobManagementOptions раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем исходного файла <br/> или потока в течение времени жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает <br/> улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) <br/> не может быть изменён в течение времени жизни экземпляра Presentation. Это пример: |
| [`is_temporary_files_allowed`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что значительно <br/> уменьшает потребление памяти, но требует разрешений на создание файлов.<br/> Все файлы будут удалены после завершения работы с презентацией. |
| [`temp_files_root_path`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Корневой путь, в котором будут создаваться временные файлы. По умолчанию будет использован системный временный каталог. <br/> Процесс-хост должен иметь разрешения на <br/> создание файлов и папок в этом месте. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB<br/> загружаются в память; только после достижения этого предела используются альтернативные механизмы (например, временные<br/> файлы). Хранение BLOB в памяти максимизирует производительность, но может привести к высокому использованию памяти. Используйте<br/> это свойство, чтобы адаптировать поведение под вашу среду или требования. |

### См. также
* класс [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)