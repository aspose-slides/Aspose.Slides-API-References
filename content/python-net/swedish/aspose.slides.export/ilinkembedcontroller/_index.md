---
title: ILinkEmbedController class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController klass

Callback-gränssnitt som används för att bestämma hur objekt ska behandlas under sparning.

ILinkEmbedController-typen exponerar följande medlemmar:

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/sv/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Bestämmer var objektet ska lagras.<br/>            Denna metod kallas en gång för varje objekt-id.<br/>            Det garanteras inte att det inte finns två objekt med samma data, semanticName och contentType men med olika id. |
| [`get_url(self, id, referrer)`](/slides/python-net/sv/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Returnerar en URL till ett externt objekt.<br/>            Denna metod kallas alltid om **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returnerade [`LinkEmbedDecision.LINK`](/slides/python-net/sv/aspose.slides.export/linkembeddecision/LINK) och kan kallas om **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returnerade [`LinkEmbedDecision.EMBED`](/slides/python-net/sv/aspose.slides.export/linkembeddecision/EMBED) men inbäddning är omöjlig.<br/>            Kan kallas flera gånger för samma objekt-id. |
| [`save_external(self, id, entity_data)`](/slides/python-net/sv/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Sparar externt objekt. |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)