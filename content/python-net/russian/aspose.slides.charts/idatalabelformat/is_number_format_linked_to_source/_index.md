---
title: is_number_format_linked_to_source property
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source свойство
Чтение/запись **bool**.

### Примечания

Если родителем этого объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это
            свойство получает или задает значение по умолчанию свойства IsNumberFormatLinkedToSource для новых 
            меток данных в коллекции DataLabelCollection.
            Установка этого свойства со значением также задает это значение свойству IsNumberFormatLinkedToSource 
            для всех меток данных в коллекции DataLabelCollection
            (например, "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" приводит к тому, 
            что у всех DataLabels[i].IsNumberFormatLinkedToSource значение равно val).

### Определение:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### См. также
* класс [`IDataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/idatalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)