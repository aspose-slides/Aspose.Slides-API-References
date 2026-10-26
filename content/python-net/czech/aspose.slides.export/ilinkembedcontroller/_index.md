---
title: ILinkEmbedController class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController třída

Rozhraní zpětného volání použité k určení, jak má být objekt zpracován během ukládání.

Typ ILinkEmbedController vystavuje následující členy:

## Metody

| Method | Description |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/cs/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Určuje, kde má být objekt uložen.<br/>            Tato metoda je volána jednou pro každé ID objektu.<br/>            Není zaručeno, že nebudou dva objekty se stejnými daty, semanticName a contentType, ale s odlišným ID. |
| [`get_url(self, id, referrer)`](/slides/python-net/cs/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Vrací URL na externí objekt.<br/>            Tato metoda je vždy volána, pokud **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.LINK`](/slides/python-net/cs/aspose.slides.export/linkembeddecision/LINK) a může být volána, pokud **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.EMBED`](/slides/python-net/cs/aspose.slides.export/linkembeddecision/EMBED), ale vložení není možné.<br/>            Může být volána vícekrát pro stejné ID objektu. |
| [`save_external(self, id, entity_data)`](/slides/python-net/cs/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Uloží externí objekt. |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)