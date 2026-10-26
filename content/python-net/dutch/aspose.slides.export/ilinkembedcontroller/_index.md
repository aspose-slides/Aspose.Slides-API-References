---
title: ILinkEmbedController class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController klasse

Callback interface die wordt gebruikt om te bepalen hoe een object moet worden verwerkt tijdens het opslaan.

Het type ILinkEmbedController bevat de volgende leden:

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/nl/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Bepaalt waar het object moet worden opgeslagen.<br/>            Deze methode wordt één keer aangeroepen voor elke object-id.<br/>            Het is niet gegarandeerd dat er geen twee objecten zijn met dezelfde gegevens, semanticName en contentType maar met een andere id. |
| [`get_url(self, id, referrer)`](/slides/python-net/nl/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Retourneert een URL naar een extern object.<br/>            Deze methode wordt altijd aangeroepen als **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/nl/aspose.slides.export/linkembeddecision/LINK) heeft geretourneerd en kan worden aangeroepen als **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/nl/aspose.slides.export/linkembeddecision/EMBED) heeft geretourneerd maar insluiten is onmogelijk.<br/>            Kan meerdere keren worden aangeroepen voor dezelfde object-id. |
| [`save_external(self, id, entity_data)`](/slides/python-net/nl/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Slaat een extern object op. |


### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)