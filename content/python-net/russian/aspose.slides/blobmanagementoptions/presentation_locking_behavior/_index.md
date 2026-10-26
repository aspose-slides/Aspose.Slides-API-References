---
title: presentation_locking_behavior property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior свойство
Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить расход памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение времени жизни экземпляра Presentation.

### Определение:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### См. также
* класс [`BlobManagementOptions`](/slides/python-net/ru/aspose.slides/blobmanagementoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)