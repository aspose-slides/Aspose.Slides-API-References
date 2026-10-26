---
title: app_version property
second_title: Referencia de la API .NET de Aspose.Slides para Python
description: 
type: docs
url: /es/aspose.slides/idocumentproperties/app_version/
weight: 90
---
## app_version propiedad
Returns the app version.
            Solo lectura **str**.


### Observaciones

The content of this element shall be in the form XX.YYYY, where X and Y represent numerical values;
            otherwise, the document shall be considered non-conformant.
            Aspose.Slides represents its version in the format XX.YYZZ, where:
            XX - versión mayor
            YY - versión menor
            ZZ - versión de parche
            For example, the value 23.0105 means Aspose.Slides version 23.1.5.

### Definición:
```python
@property
def app_version(self):
    ...
```


### Ver también
* clase [`IDocumentProperties`](/slides/python-net/es/aspose.slides/idocumentproperties)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)