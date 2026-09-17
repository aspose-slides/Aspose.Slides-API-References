---
title: last_saved_time property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time propiedad
Returns the date a presentation was last modified.
            Los valores están en UTC.
            Solo de lectura en caso de Presentation.DocumentProperties (porque se actualizará internamente durante el proceso de guardado del objeto IPresentation). 
            Puede modificarse a través de una instancia de DocumentProperties devuelta por el método [`IPresentationInfo.read_document_properties`](/slides/python-net/es/aspose.slides/ipresentationinfo/read_document_properties)
            Consulte el ejemplo en el resumen del método **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**.

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
* clase [`DocumentProperties`](/slides/python-net/es/aspose.slides/documentproperties)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)