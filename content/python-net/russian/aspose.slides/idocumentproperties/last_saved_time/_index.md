---
title: last_saved_time property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time свойство
Возвращает дату последнего изменения презентации.
Значения указаны в UTC.P
Только для чтения в случае Presentation.DocumentProperties (поскольку он будет обновляться внутренне во время процесса сохранения объекта IPresentation).
Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [`IPresentationInfo.read_document_properties`](/slides/python-net/ru/aspose.slides/ipresentationinfo/read_document_properties)
Смотрите пример в **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** резюме метода.

### Определение:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### См. также
* класс [`IDocumentProperties`](/slides/python-net/ru/aspose.slides/idocumentproperties)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)