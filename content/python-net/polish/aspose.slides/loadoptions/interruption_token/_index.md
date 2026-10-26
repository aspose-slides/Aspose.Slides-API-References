---
title: interruption_token property
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token właściwość
Token służący do monitorowania żądań przerwania.

Ten token zarządza całym okresem życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). Każda długotrwała operacja, taka jak ładowanie lub zapisywanie prezentacji, zostanie przerwana poprzez wywołanie metody [`InterruptionTokenSource.interrupt`](/slides/python-net/pl/aspose.slides/interruptiontokensource/interrupt) klasy [`InterruptionTokenSource`](/slides/python-net/pl/aspose.slides/interruptiontokensource).

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
* klasa [`InterruptionTokenSource`](/slides/python-net/pl/aspose.slides/interruptiontokensource)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* klasa [`LoadOptions`](/slides/python-net/pl/aspose.slides/loadoptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)