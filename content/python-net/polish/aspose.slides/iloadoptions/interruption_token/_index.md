---
title: interruption_token property
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token właściwość
Token służący do monitorowania żądań przerwania.

Ten token zarządza całym okresem życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [`IInterruptionTokenSource.interrupt`](/slides/python-net/pl/aspose.slides/iinterruptiontokensource/interrupt) obiektu [`IInterruptionTokenSource`](/slides/python-net/pl/aspose.slides/iinterruptiontokensource).

### Definicja:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Zobacz także
* klasa [`IInterruptionTokenSource`](/slides/python-net/pl/aspose.slides/iinterruptiontokensource)
* klasa [`ILoadOptions`](/slides/python-net/pl/aspose.slides/iloadoptions)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)