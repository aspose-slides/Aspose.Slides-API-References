---
title: interruption_token property
second_title: Aspose.Slides pro Python přes .NET – reference API
description: 
type: docs
url: /cs/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token vlastnost
Token, který sleduje požadavky na přerušení.

            Tento token spravuje celou životnost instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). Jakákoli dlouho běžící operace, například prezentace 
            načítání nebo ukládání, bude přerušena voláním metody [`IInterruptionTokenSource.interrupt`](/slides/python-net/cs/aspose.slides/iinterruptiontokensource/interrupt) 
            [`IInterruptionTokenSource`](/slides/python-net/cs/aspose.slides/iinterruptiontokensource).

### Definice:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Viz také
* třída [`IInterruptionTokenSource`](/slides/python-net/cs/aspose.slides/iinterruptiontokensource)
* třída [`ILoadOptions`](/slides/python-net/cs/aspose.slides/iloadoptions)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)