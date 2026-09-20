---
title: get_visual_bounds method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato.

### Restituisce

Un **aspose.slides.RectangleF** che rappresenta i limiti visivi della forma
             nelle coordinate della diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Osservazioni

Il rettangolo restituito rappresenta i limiti allineati agli assi di tutto il contenuto
             prodotto dalla forma durante il rendering nello spazio di coordinate della diapositiva.
            
             Questi limiti possono differire dai limiti del modello della forma
             ([`Shape.x`](/slides/python-net/it/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/it/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/it/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/it/aspose.slides/shape/height))
             e possono contenere coordinate negative se il contenuto renderizzato si estende
             al di là dell'origine della diapositiva.
            
             I limiti visivi tengono conto di aspetti legati al rendering come
             le trasformazioni (ad esempio, rotazione), la larghezza e le unioni del tratto,
             il layout del testo e l'overflow, la geometria di SmartArt e altri effetti di layout
             che influenzano l'aspetto finale renderizzato della forma.
            
             I limiti restituiti non sono ritagliati al rettangolo della diapositiva.



### Vedi anche
* classe [`Connector`](/slides/python-net/it/aspose.slides/connector)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)