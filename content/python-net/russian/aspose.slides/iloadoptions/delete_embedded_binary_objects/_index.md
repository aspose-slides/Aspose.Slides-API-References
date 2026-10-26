---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects свойство
Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации.

Типы встроенных двоичных объектов:

* VBA Project [`IPresentation.vba_project`](/slides/python-net/ru/aspose.slides/ipresentation/vba_project)
* OLE Object встроенные данные [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control бинарные данные [`IControl.active_x_control_binary`](/slides/python-net/ru/aspose.slides/icontrol/active_x_control_binary)

Чтение/запись **bool**.

### Примечания

По умолчанию **false**.

### Определение:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Смотрите также
* class [`ILoadOptions`](/slides/python-net/ru/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)