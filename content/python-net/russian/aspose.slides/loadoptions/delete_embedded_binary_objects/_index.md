---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects свойство
Определяет, будет ли Aspose.Slides удалять все вложенные бинарные объекты при загрузке презентации.
            
Типы вложенных бинарных объектов:


* VBA Project [`IPresentation.vba_project`](/slides/python-net/ru/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/ru/aspose.slides/icontrol/active_x_control_binary)


Чтение/запись **bool**.


### Примечания

По умолчанию **false** .

### Определение:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```


### См. также
* класс [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)