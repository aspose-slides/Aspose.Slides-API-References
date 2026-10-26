---
title: get_url method
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Devuelve una URL a un objeto externo.
            Este método siempre se llama si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.LINK`](/slides/python-net/es/aspose.slides.export/linkembeddecision/LINK) y puede llamarse si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.EMBED`](/slides/python-net/es/aspose.slides.export/linkembeddecision/EMBED) pero la incrustación es imposible.
            Puede llamarse varias veces para el mismo id de objeto.

### Devuelve

URL del objeto externo o None si este objeto debe ser ignorado.



```python
def get_url(self, id, referrer):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | **int** | Identificador del objeto. Este identificador es único en toda la operación de guardado. |
| referrer | **int** | identificador del objeto que hace referencia o 0, si el objeto es referenciado por el documento raíz. Puede usarse para generar un enlace relativo. |



### Ver también
* clase [`ILinkEmbedController`](/slides/python-net/es/aspose.slides.export/ilinkembedcontroller)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)