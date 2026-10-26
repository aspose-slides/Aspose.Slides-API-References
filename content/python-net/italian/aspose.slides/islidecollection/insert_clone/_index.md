---
title: insert_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Inserisce una copia di una slide specificata nella posizione specificata della collezione.

### Restituisce

Slide inserita.



```python
def insert_clone(self, index, source_slide):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova slide. |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Slide da clonare. |

### Osservazioni

Durante la clonazione di una slide tra presentazioni diverse, anche il master della slide può essere clonato.  
Un registro interno è usato per tenere traccia dei master clonato automaticamente, allo scopo di evitare la creazione di più cloni dello stesso master slide.  
La clonazione manuale dei master slide non sarà né impedita né registrata.  
Se hai bisogno di maggiore controllo sul processo di clonazione, usa  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** o  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** per clonare slide e  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** per clonare master.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Inserisce una copia di una slide specificata nella posizione specificata della collezione.

### Restituisce

Slide inserita.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova slide. |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Slide da clonare. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Slide di layout per una nuova slide. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Inserisce una copia di una slide sorgente specificata nella posizione specificata della collezione.  
Il layout appropriato verrà selezionato automaticamente dal master specificato  
(layout appropriato è il layout con lo stesso Tipo o Nome del layout della slide sorgente). Se non esiste un layout appropriato, il layout della slide sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà generata un'eccezione PptxEditException (se allowCloneMissingLayout è false).

### Restituisce

Slide inserita.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova slide. |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Slide da clonare. |
| dest_master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Master slide per una nuova slide. |
| allow_clone_missing_layout | **bool** | Se non esiste un layout appropriato nel master specificato, allora il layout della <br/><br/>            slide sorgente verrà clonato (se allowCloneMissingLayout è true) o <br/><br/>            verrà lanciata un'eccezione PptxEditException (se allowCloneMissingLayout è false). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Lanciata se non esiste un layout appropriato nel master specificato e <br/>            allowCloneMissingLayout è false. |



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`ISlideCollection`](/slides/python-net/it/aspose.slides/islidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)