---
title: add_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Aggiunge una copia di una diapositiva layout specificata alla presentazione.

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

Durante la clonazione di un layout tra presentazioni diverse, anche il master del layout può essere clonato per mantenere la formattazione originale.  
Un registro interno viene utilizzato per tracciare i master clonati automaticamente al fine di evitare la creazione di più cloni della stessa diapositiva master.  
La clonazione manuale delle diapositive master non sarà né impedita né registrata.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Aggiunge una copia di una diapositiva layout specificata alla presentazione.

### Restituisce

Diapositiva aggiunta.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Diapositiva da clonare. |
| dest_master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Diapositiva master per un nuovo layout. |

### Osservazioni

1) Il nuovo layout sarà collegato al master definito nella presentazione di destinazione.  
Quindi è l'analogo di copia/incolla con l'opzione "Usa tema di destinazione" in PowerPoint.  
2) L'analogo di questo metodo è il metodo **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** accessibile tramite la proprietà [`IMasterSlide.layout_slides`](/slides/python-net/it/aspose.slides/imasterslide/layout_slides).



### Vedi anche
* class [`GlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/globallayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)