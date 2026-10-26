---
title: add_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Aggiunge una copia di una diapositiva layout specificata alla fine della raccolta.

### Restituisce

Diapositiva aggiunta.



```python
def add_clone(self, source_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Diapositiva da clonare. |

### Osservazioni

1) Il nuovo layout sarà collegato alla diapositiva master padre per questa raccolta di diapositive layout.  
            Quindi è l'analogo di copia/incolla con l'opzione "Usa tema di destinazione" in PowerPoint.  
            2) Il metodo analogo a questo è il metodo **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** accessibile tramite la proprietà [`IPresentation.layout_slides`](/slides/python-net/it/aspose.slides/ipresentation/layout_slides).



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)