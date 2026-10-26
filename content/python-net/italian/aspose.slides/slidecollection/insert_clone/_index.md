---
title: insert_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

### Valore restituito

Diapositiva inserita.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova diapositiva. |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |

### Osservazioni

Durante la clonazione di una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anch'esso.  
            Un registro interno viene utilizzato per tenere traccia dei master clonati automaticamente al fine di evitare la creazione di più cloni dello stesso master.  
            La clonazione manuale dei master non sarà né impedita né registrata.  
            Se è necessario un maggiore controllo sul processo di clonazione, utilizzare  
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** oppure  
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** per clonare le diapositive e  
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** per clonare i master.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

### Valore restituito

Diapositiva inserita.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova diapositiva. |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Layout della diapositiva per la nuova diapositiva. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della collezione.  
            Il layout appropriato sarà selezionato automaticamente dal master specificato  
            (il layout appropriato è il layout con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) oppure verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout è false).

### Valore restituito

Diapositiva inserita.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | Indice della nuova diapositiva. |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| dest_master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Master slide per la nuova diapositiva. |
| allow_clone_missing_layout | **bool** | Se non esiste un layout appropriato nel master specificato, allora il layout della <br/><br/>            diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o <br/><br/>            verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout è false). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Sollevata se non esiste un layout appropriato nel master specificato e <br/>            allowCloneMissingLayout è false. |



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* classe [`SlideCollection`](/slides/python-net/it/aspose.slides/slidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)