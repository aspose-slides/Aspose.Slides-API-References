---
title: add_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/igloballayoutslidecollection/add_clone/
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
Quando si clona un layout tra presentazioni diverse, il master del layout può essere clonato anche per mantenere la formattazione di origine. Un registro interno è usato per tenere traccia dei master clonati automaticamente, evitando la creazione di più cloni dello stesso master slide. Il clonaggio manuale dei master slide non sarà né impedito né registrato.

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
| dest_master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Master slide per un nuovo layout. |

### Osservazioni
Il nuovo layout sarà collegato al master definito nella presentazione di destinazione. Quindi è analogo a copia/incolla con l'opzione "Usa tema di destinazione" in PowerPoint.

### Vedi anche
* classe [`IGlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/igloballayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)