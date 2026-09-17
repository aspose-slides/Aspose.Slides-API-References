---
title: last_saved_time property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time propiedad
Devuelve la fecha en que una presentación fue modificada por última vez.
            Los valores están en UTC.P
            Solo lectura en el caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). 
            Puede cambiarse mediante la instancia DocumentProperties devuelta por el método [`IPresentationInfo.read_document_properties`](/slides/python-net/es/aspose.slides/ipresentationinfo/read_document_properties)
            Consulte el ejemplo en **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary.

### Definición:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### Ver también
* clase [`IDocumentProperties`](/slides/python-net/es/aspose.slides/idocumentproperties)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)