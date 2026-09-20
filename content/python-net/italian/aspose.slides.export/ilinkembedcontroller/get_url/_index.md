---
title: get_url method
second_title: Aspose.Slides per Python tramite l'API .NET
description: 
type: docs
url: /it/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Restituisce un URL a un oggetto esterno.
            Questo metodo è sempre chiamato se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** restituito [`LinkEmbedDecision.LINK`](/slides/python-net/it/aspose.slides.export/linkembeddecision/LINK) e può essere chiamato se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** restituito [`LinkEmbedDecision.EMBED`](/slides/python-net/it/aspose.slides.export/linkembeddecision/EMBED) ma l'incorporamento è impossibile.
            Può essere chiamato più volte per lo stesso ID oggetto.

### Returns

URL dell'oggetto esterno o None se questo oggetto deve essere ignorato.



```python
def get_url(self, id, referrer):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| id | **int** | ID dell'oggetto. Questo ID è unico per l'intera operazione di salvataggio. |
| referrer | **int** | ID dell'oggetto referenziante o 0, se l'oggetto è referenziato dal documento radice. Può essere usato per generare un link relativo. |



### See Also
* classe [`ILinkEmbedController`](/slides/python-net/it/aspose.slides.export/ilinkembedcontroller)
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)