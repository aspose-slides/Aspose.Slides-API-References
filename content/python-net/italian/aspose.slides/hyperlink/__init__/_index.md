---
title: Hyperlink constructor
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Crea un'istanza di un collegamento ipertestuale.


```python
def __init__(self, url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| url | **str** | URL del collegamento ipertestuale. |


## __init__(self, slide) {#islide}
Crea un'istanza di un collegamento ipertestuale che punta a una diapositiva specifica.  
Nota: il collegamento ipertestuale creato deve essere assegnato a qualche oggetto della stessa presentazione, altrimenti il link sarà salvato come NoAction.


```python
def __init__(self, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva di destinazione. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Crea un'istanza di un collegamento ipertestuale usando un altro collegamento ipertestuale come origine, sovrascrivendo le proprietà secondarie.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink) | Collegamento ipertestuale di origine |
| target_frame | **str** | Frame di destinazione |
| tooltip | **str** | Testo del suggerimento |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Vedi anche
* classe [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)