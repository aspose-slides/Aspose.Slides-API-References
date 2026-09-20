---
title: ILinkEmbedController class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController classe

Interfaccia di callback usata per determinare come l'oggetto dovrebbe essere elaborato durante il salvataggio.

Il tipo ILinkEmbedController espone i seguenti membri:

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/it/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Determina dove l'oggetto dovrebbe essere memorizzato.<br/>            Questo metodo viene chiamato una volta per ogni ID oggetto.<br/>            Non è garantito che non esistano due oggetti con gli stessi dati, semanticName e contentType ma con ID diversi. |
| [`get_url(self, id, referrer)`](/slides/python-net/it/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Restituisce un URL a un oggetto esterno.<br/>            Questo metodo è sempre chiamato se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** ha restituito [`LinkEmbedDecision.LINK`](/slides/python-net/it/aspose.slides.export/linkembeddecision/LINK) e può essere chiamato se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** ha restituito [`LinkEmbedDecision.EMBED`](/slides/python-net/it/aspose.slides.export/linkembeddecision/EMBED) ma l'incorporamento è impossibile.<br/>            Può essere chiamato più volte per lo stesso ID oggetto. |
| [`save_external(self, id, entity_data)`](/slides/python-net/it/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Salva l'oggetto esterno. |


### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)