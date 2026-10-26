---
title: presentation_locking_behavior property
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior свойство
Это свойство определяет, может ли экземпляр класса Presentation быть владельцем исходного файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает уменьшить потребление памяти и повысить производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение срока жизни экземпляра Presentation. Пример:

### Определение:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### Смотрите также
* класс [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)