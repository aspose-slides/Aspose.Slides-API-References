---
title: get_visual_bounds method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ottiene i confini visivi della forma calcolati dal suo contenuto renderizzato.

### Restituisce

Un **aspose.slides.RectangleF** che rappresenta i confini visivi della forma
             nelle coordinate della diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Osservazioni

Il rettangolo restituito rappresenta i confini allineati agli assi di tutto il contenuto
             prodotto dalla forma durante il rendering nello spazio delle coordinate della diapositiva.
            
             Questi confini possono differire dai confini del modello della forma
             ([`Shape.x`](/slides/python-net/it/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/it/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/it/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/it/aspose.slides/shape/height))
             e possono contenere coordinate negative se il contenuto renderizzato si estende
             oltre l'origine della diapositiva.
            
             I confini visivi tengono conto degli aspetti relativi al rendering, quali
             trasformazioni (ad esempio, rotazione), larghezza del tratto e giunzioni,
             layout del testo e overflow, geometria di SmartArt e altri effetti di layout
             che influenzano l'aspetto finale renderizzato della forma.
            
             I confini restituiti non sono tagliati al rettangolo della diapositiva.



### Vedi anche
* classe [`ZoomFrame`](/slides/python-net/it/aspose.slides/zoomframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)