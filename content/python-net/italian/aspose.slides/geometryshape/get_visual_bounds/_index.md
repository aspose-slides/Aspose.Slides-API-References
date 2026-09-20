---
title: get_visual_bounds method
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Restituisce i limiti visivi della forma calcolati dal suo contenuto renderizzato.

### Restituisce

Un **aspose.slides.RectangleF** che rappresenta i limiti visivi della forma
             nelle coordinate della diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Note

Il rettangolo restituito rappresenta i limiti allineati agli assi di tutti i contenuti prodotti dalla forma durante il rendering nello spazio delle coordinate della diapositiva.
            
Questi limiti possono differire dai limiti del modello della forma
             ([`Shape.x`](/slides/python-net/it/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/it/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/it/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/it/aspose.slides/shape/height))
             e possono contenere coordinate negative se il contenuto renderizzato si estende oltre l'origine della diapositiva.
            
I limiti visivi tengono conto degli aspetti relativi al rendering come trasformazioni (ad esempio, rotazione), larghezza e giunzioni del tratto, layout del testo e overflow, geometria SmartArt e altri effetti di layout che influenzano l'aspetto finale renderizzato della forma.
            
I limiti restituiti non sono ritagliati al rettangolo della diapositiva.



### Vedi anche
* classe [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)