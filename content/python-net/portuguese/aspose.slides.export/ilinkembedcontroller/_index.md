---
title: ILinkEmbedController class
second_title: Aspose.Slides para Python via Referência de API .NET
description: 
type: docs
url: /pt/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController classe

Interface de retorno de chamada usada para determinar como o objeto deve ser processado durante a gravação.

O tipo ILinkEmbedController expõe os seguintes membros:

## Métodos

| Method | Description |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/pt/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Determina onde o objeto deve ser armazenado.<br/>            Este método é chamado uma vez para cada ID de objeto.<br/>            Não há garantia de que não haverá dois objetos com os mesmos dados, semanticName e contentType, mas com IDs diferentes. |
| [`get_url(self, id, referrer)`](/slides/python-net/pt/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Retorna uma URL para um objeto externo.<br/>            Este método sempre é chamado se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** retornou [`LinkEmbedDecision.LINK`](/slides/python-net/pt/aspose.slides.export/linkembeddecision/LINK) e pode ser chamado se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** retornou [`LinkEmbedDecision.EMBED`](/slides/python-net/pt/aspose.slides.export/linkembeddecision/EMBED) mas a incorporação é impossível.<br/>            Pode ser chamado múltiplas vezes para o mesmo ID de objeto. |
| [`save_external(self, id, entity_data)`](/slides/python-net/pt/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Salva o objeto externo. |


### Ver também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)