---
title: interruption_token property
second_title: Aspose.Slides para Python vía .NET API Referencia
description: 
type: docs
url: /es/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token propiedad
El token para monitorizar solicitudes de interrupción.
            
Este token gestiona la vida completa de la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). Cualquier operación de larga duración, como cargar o guardar la presentación, será interrumpida llamando al método [`InterruptionTokenSource.interrupt`](/slides/python-net/es/aspose.slides/interruptiontokensource/interrupt) del [`InterruptionTokenSource`](/slides/python-net/es/aspose.slides/interruptiontokensource).

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
* clase [`InterruptionTokenSource`](/slides/python-net/es/aspose.slides/interruptiontokensource)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* clase [`LoadOptions`](/slides/python-net/es/aspose.slides/loadoptions)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)