---
title: disable_line_end_cropping property
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides.export/svgoptions/disable_line_end_cropping/
weight: 90
---
## disable_line_end_cropping свойство
В SVG 1.1 отсутствует возможность задавать отступы для маркеров.
            У двигателя записи SVG Aspose.Slides есть обходной путь для этой проблемы:
            он обрезает конец линии со стрелкой, поэтому линия не перекрывает маркеры.
            Эта опция отключает такое поведение.
            Чтение/запись **bool**.

### Определение:
```python
@property
def disable_line_end_cropping(self):
    ...

@disable_line_end_cropping.setter
def disable_line_end_cropping(self, value):
    ...
```


### См. также
* класс [`SVGOptions`](/slides/python-net/ru/aspose.slides.export/svgoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)