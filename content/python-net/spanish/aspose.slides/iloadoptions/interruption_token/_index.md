---
title: interruption_token property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token propiedad
El token para monitorear solicitudes de interrupción.
            
            Este token gestiona toda la vida útil de la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). Cualquier operación de larga duración, como la carga o guardado de una presentación, se interrumpirá llamando al método [`IInterruptionTokenSource.interrupt`](/slides/python-net/es/aspose.slides/iinterruptiontokensource/interrupt) del [`IInterruptionTokenSource`](/slides/python-net/es/aspose.slides/iinterruptiontokensource).

### Definición:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### Ver también
* clase [`IInterruptionTokenSource`](/slides/python-net/es/aspose.slides/iinterruptiontokensource)
* clase [`ILoadOptions`](/slides/python-net/es/aspose.slides/iloadoptions)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)