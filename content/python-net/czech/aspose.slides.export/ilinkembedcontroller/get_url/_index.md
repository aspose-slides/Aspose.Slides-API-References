---
title: get_url method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Vrací URL na externí objekt.
            Tato metoda je vždy volána, pokud **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** vrátil [`LinkEmbedDecision.LINK`](/slides/python-net/cs/aspose.slides.export/linkembeddecision/LINK) a může být volána, pokud **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** vrátil [`LinkEmbedDecision.EMBED`](/slides/python-net/cs/aspose.slides.export/linkembeddecision/EMBED), ale vložení není možné.
            Může být volána vícekrát pro stejný identifikátor objektu.

### Návratová hodnota

URL externího objektu nebo None, pokud má být tento objekt ignorován.



```python
def get_url(self, id, referrer):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| id | **int** | Identifikátor objektu. Tento identifikátor je v rámci operace jedinečný. |
| referrer | **int** | Identifikátor odkazujícího objektu nebo 0, pokud je objekt odkazován kořenovým dokumentem. Může být použit k vytvoření relativního odkazu. |



### Viz také
* třída [`ILinkEmbedController`](/slides/python-net/cs/aspose.slides.export/ilinkembedcontroller)
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)