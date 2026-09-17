---
title: separator property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## свойство separator
Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме.
            Чтение/запись **str**.


### Примечания

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to all DataLabels[i].Separator is equal to val).

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
* класс [`DataLabelFormat`](/slides/python-net/ru/aspose.slides.charts/datalabelformat)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)