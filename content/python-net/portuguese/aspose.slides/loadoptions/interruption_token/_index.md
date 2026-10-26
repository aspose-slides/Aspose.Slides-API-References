---
title: interruption_token property
second_title: Aspose.Slides para Python via .NET API Reference
description: 
type: docs
url: /pt/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token propriedade
O token para monitorar solicitações de interrupção.
            
            Este token gerencia todo o tempo de vida da instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). Qualquer operação de longa duração, como carregamento ou salvamento da apresentação, será interrompida ao chamar o método [`InterruptionTokenSource.interrupt`](/slides/python-net/pt/aspose.slides/interruptiontokensource/interrupt) do [`InterruptionTokenSource`](/slides/python-net/pt/aspose.slides/interruptiontokensource).

### Definição:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### Veja Também
* classe [`InterruptionTokenSource`](/slides/python-net/pt/aspose.slides/interruptiontokensource)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* classe [`LoadOptions`](/slides/python-net/pt/aspose.slides/loadoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)