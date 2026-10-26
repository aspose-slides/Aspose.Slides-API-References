---
title: interruption_token property
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token свойство
Токен для отслеживания запросов на прерывание.
            
            Этот токен управляет жизненным циклом всего экземпляра [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). Любая долгосрочная операция, такая как загрузка 
            или сохранение презентации, будет прервана вызовом метода [`InterruptionTokenSource.interrupt`](/slides/python-net/ru/aspose.slides/interruptiontokensource/interrupt) у 
            [`InterruptionTokenSource`](/slides/python-net/ru/aspose.slides/interruptiontokensource).

### Определение:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### См. также
* класс [`InterruptionTokenSource`](/slides/python-net/ru/aspose.slides/interruptiontokensource)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* класс [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)