---
title: separator property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator свойство
Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме.
            Чтение/запись **str**.

### Примечания

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это
            свойство получает или задает значение по умолчанию свойства Separator для новых
            подписей данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству Separator
            для всех подписей данных в коллекции DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" приводит к 
            тому, что все DataLabels[i].Separator равны val).

### Определение:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)