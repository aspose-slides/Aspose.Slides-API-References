---
title: max_blobs_bytes_in_memory property
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory свойство
Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB
            загружаются в память; только когда достигается этот предел, применяются альтернативные механизмы (например, временные
            файлы). Хранение BLOB в памяти повышает производительность, но может привести к высокому потреблению памяти. Используйте
            это свойство, чтобы адаптировать поведение к вашей среде или требованиям.

### Примечание

Это свойство игнорируется, если [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) установлен в false, поскольку в этом случае память является единственным доступным местом хранения, и ограничение использования in-memory BLOB не оказывает эффекта.

### Определение:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### См. также
* класс [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)