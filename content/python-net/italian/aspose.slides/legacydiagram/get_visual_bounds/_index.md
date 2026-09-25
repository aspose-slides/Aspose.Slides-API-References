---
title: get_visual_bounds method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato.

### Restituisce

Un [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef) che rappresenta i limiti visivi della forma nelle coordinate della diapositiva
             in coordinate della diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Osservazioni

Il rettangolo restituito rappresenta i limiti allineati agli assi di tutti i contenuti
             prodotti dalla forma durante il rendering nello spazio di coordinate della diapositiva.
            
             Questi limiti possono differire dai limiti del modello della forma
             ([`Shape.x`](/slides/python-net/it/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/it/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/it/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/it/aspose.slides/shape/height))
             e possono contenere coordinate negative se il contenuto renderizzato si estende
             oltre l'origine della diapositiva.
            
             I limiti visivi tengono conto degli aspetti legati al rendering, come
             le trasformazioni (ad esempio, rotazione), la larghezza del tratto e le giunzioni,
             il layout del testo e l'overflow, la geometria di SmartArt e altri effetti di layout
             che influenzano l'aspetto finale renderizzato della forma.
            
             I limiti restituiti non sono ritagliati al rettangolo della diapositiva.



### Vedi anche
* classe [`LegacyDiagram`](/slides/python-net/it/aspose.slides/legacydiagram)
* classe [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)