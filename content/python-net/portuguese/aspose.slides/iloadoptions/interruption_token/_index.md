---
title: interruption_token property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## propriedade interruption_token
O token para monitorar solicitações de interrupção.

Este token gerencia o tempo de vida de toda a instância [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). Qualquer operação de longa duração, como carregamento ou salvamento de apresentação, será interrompida ao chamar o método [`IInterruptionTokenSource.interrupt`](/slides/python-net/pt/aspose.slides/iinterruptiontokensource/interrupt) do [`IInterruptionTokenSource`](/slides/python-net/pt/aspose.slides/iinterruptiontokensource).

### Definição:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Ver Também
* classe [`IInterruptionTokenSource`](/slides/python-net/pt/aspose.slides/iinterruptiontokensource)
* classe [`ILoadOptions`](/slides/python-net/pt/aspose.slides/iloadoptions)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)