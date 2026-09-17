---
title: interruption_token property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token свойство
Токен для отслеживания запросов на прерывание.
            
            Этот токен управляет всем жизненным циклом экземпляра [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). Любая длительная операция, например загрузка или сохранение презентации, будет прервана вызовом метода [`IInterruptionTokenSource.interrupt`](/slides/python-net/ru/aspose.slides/iinterruptiontokensource/interrupt) объекта [`IInterruptionTokenSource`](/slides/python-net/ru/aspose.slides/iinterruptiontokensource).

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
* класс [`IInterruptionTokenSource`](/slides/python-net/ru/aspose.slides/iinterruptiontokensource)
* класс [`ILoadOptions`](/slides/python-net/ru/aspose.slides/iloadoptions)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)