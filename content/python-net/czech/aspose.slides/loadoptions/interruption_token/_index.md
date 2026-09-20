---
title: interruption_token property
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token vlastnost
Token slouží ke sledování požadavků na přerušení.
            
            Tento token řídí celou životnost instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). Každá dlouhotrvající operace, jako je načítání 
            nebo ukládání prezentace, bude přerušena zavoláním metody [`InterruptionTokenSource.interrupt`](/slides/python-net/cs/aspose.slides/interruptiontokensource/interrupt) třídy 
            [`InterruptionTokenSource`](/slides/python-net/cs/aspose.slides/interruptiontokensource).

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
* třída [`InterruptionTokenSource`](/slides/python-net/cs/aspose.slides/interruptiontokensource)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* třída [`LoadOptions`](/slides/python-net/cs/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)