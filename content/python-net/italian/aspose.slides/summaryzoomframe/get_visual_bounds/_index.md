---
title: get_visual_bounds method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Ottiene i confini visivi della forma calcolati dal suo contenuto renderizzato.

### Restituisce

Un [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef) che rappresenta i confini visivi della forma nelle coordinate della diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Osservazioni

Il rettangolo restituito rappresenta i confini allineati agli assi di tutti i contenuti
             prodotti dalla forma durante il rendering nello spazio delle coordinate della diapositiva.
             
             Questi confini possono differire dai confini modello della forma
             ([`Shape.x`](/slides/python-net/it/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/it/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/it/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/it/aspose.slides/shape/height))
             e possono contenere coordinate negative se il contenuto renderizzato si estende
             oltre l'origine della diapositiva.
             
             I confini visivi tengono conto di aspetti legati al rendering come
             trasformazioni (ad esempio, rotazione), larghezza e giunzioni del tratto,
             layout e overflow del testo, geometria di SmartArt e altri effetti di layout
             che influenzano l'aspetto finale renderizzato della forma.
             
             I confini restituiti non sono ritagliati al rettangolo della diapositiva.



### Vedi anche
* classe [`SummaryZoomFrame`](/slides/python-net/it/aspose.slides/summaryzoomframe)
* classe [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)