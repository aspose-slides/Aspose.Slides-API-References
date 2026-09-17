---
title: ILinkEmbedController class
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController clase

Interfaz de devolución de llamada usada para determinar cómo debe procesarse el objeto durante el guardado.

El tipo ILinkEmbedController expone los siguientes miembros:

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/es/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Determina dónde debe almacenarse el objeto.<br/>            Este método se llama una vez por cada id de objeto.<br/>            No se garantiza que no haya dos objetos con los mismos datos, semanticName y contentType pero con id diferentes. |
| [`get_url(self, id, referrer)`](/slides/python-net/es/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Devuelve una URL a un objeto externo.<br/>            Este método siempre se llama si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** devolvió [`LinkEmbedDecision.LINK`](/slides/python-net/es/aspose.slides.export/linkembeddecision/LINK) y puede llamarse si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** devolvió [`LinkEmbedDecision.EMBED`](/slides/python-net/es/aspose.slides.export/linkembeddecision/EMBED) pero la incrustación es imposible.<br/>            Puede llamarse varias veces para el mismo id de objeto. |
| [`save_external(self, id, entity_data)`](/slides/python-net/es/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Guarda el objeto externo. |

### Ver también
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)