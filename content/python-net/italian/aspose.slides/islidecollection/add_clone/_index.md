---
title: add_clone method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |

### Osservazioni

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anche.  
Il registro interno è usato per tracciare i master clonati automaticamente al fine di evitare la creazione di più cloni dello stesso master della diapositiva.  
Il clonaggio manuale dei master delle diapositive non sarà né impedito né registrato.  
Se hai bisogno di maggior controllo sul processo di clonazione, usa  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** o  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** per clonare diapositive,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** o  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** per clonare layout e  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** per clonare master.


## add_clone(self, source_slide, section) {#islide-isection}
Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Sezione per una nuova diapositiva. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Layout della diapositiva per una nuova diapositiva. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Aggiunge una copia di una diapositiva di origine specificata alla fine della raccolta.  
Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva di origine). Se non esiste un layout appropriato, il layout della diapositiva di origine verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false).

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| dest_master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Master della diapositiva per una nuova diapositiva. |
| allow_clone_missing_layout | **bool** | Se non esiste un layout appropriato nel master specificato, il layout della <br/><br/>            diapositiva di origine verrà clonato (se allowCloneMissingLayout è true) o <br/><br/>            verrà sollevata una PptxEditException (se allowCloneMissingLayout è false). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se non esiste un layout appropriato nel master specificato e <br/>            allowCloneMissingLayout è false. |



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* classe [`ISection`](/slides/python-net/it/aspose.slides/isection)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`ISlideCollection`](/slides/python-net/it/aspose.slides/islidecollection)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)