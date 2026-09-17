---
title: last_saved_time property
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time свойство
Возвращает дату последнего изменения презентации.  
Значения в UTC.  
Только для чтения в случае Presentation.DocumentProperties (поскольку будет обновляться внутренне во время процесса сохранения объекта IPresentation).  
Может быть изменено через экземпляр DocumentProperties, возвращаемый методом [`IPresentationInfo.read_document_properties`](/slides/python-net/ru/aspose.slides/ipresentationinfo/read_document_properties).  
Пожалуйста, смотрите пример в **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary.

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
* класс [`DocumentProperties`](/slides/python-net/ru/aspose.slides/documentproperties)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)