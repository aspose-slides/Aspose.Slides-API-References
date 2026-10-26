---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory свойство
Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB
            загружаются в память; только после достижения этого предела применяются альтернативные механизмы (например, временные
            файлы) применяются. Хранение BLOB в памяти максимизирует производительность, но может привести к высокому потреблению памяти. Используйте
            это свойство, чтобы адаптировать поведение под вашу среду или требования.


### Примечания

Это свойство игнорируется, если [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ru/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) установлено в false, поскольку память тогда
            единственное доступное место хранения, и ограничение использования BLOB в памяти не имеет эффекта.

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
* класс [`BlobManagementOptions`](/slides/python-net/ru/aspose.slides/blobmanagementoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)