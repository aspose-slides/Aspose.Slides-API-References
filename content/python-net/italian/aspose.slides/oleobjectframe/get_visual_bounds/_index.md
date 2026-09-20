---
title: get_visual_bounds method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Recupera i limiti visivi della forma calcolati dal suo contenuto renderizzato.

### Restituisce

Un **aspose.slides.RectangleF** che rappresenta i limiti visivi della forma nelle coordinate della diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Osservazioni

             Il rettangolo restituito rappresenta i limiti allineati agli assi di tutto il contenuto prodotto dalla forma durante il rendering nello spazio delle coordinate della diapositiva.
             
             Questi limiti possono differire dai limiti del modello della forma ([`Shape.x`](/slides/python-net/it/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/it/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/it/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/it/aspose.slides/shape/height)) e possono contenere coordinate negative se il contenuto renderizzato si estende oltre l'origine della diapositiva.
             
             I limiti visivi tengono conto degli aspetti legati al rendering, come le trasformazioni (ad esempio, la rotazione), lo spessore e le giunzioni del tratto, l'impaginazione e l'overflow del testo, la geometria di SmartArt e altri effetti di layout che influenzano l'aspetto finale renderizzato della forma.
             
             I limiti restituiti non sono ritagliati al rettangolo della diapositiva.



### Vedi anche
* classe [`OleObjectFrame`](/slides/python-net/it/aspose.slides/oleobjectframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)