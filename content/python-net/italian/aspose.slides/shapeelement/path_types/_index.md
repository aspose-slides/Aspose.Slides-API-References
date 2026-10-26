---
title: path_types property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types proprietà
Restituisce un array di valori byte che specificano il tipo di ogni punto nel percorso dell'elemento.

**0**  Indica che il punto è l'inizio di una figura.

**1**  Indica che il punto è uno dei due estremi di una linea.

**3**  Indica che il punto è un estremo o un punto di controllo di uno spline cubico di Bezier.

**7**  Maschera tutti i bit eccetto i tre bit di ordine inferiore, che indicano il tipo di punto.

**16**  Specifica che il segmento corrispondente è tratteggiato.

**32**  Specifica che il punto è un marcatore.

**128**  Specifica che il punto è l'ultimo punto in un sotto-percorso chiuso (figura).

**129**  Indica un punto dati che è sia l'estremo di un segmento di linea sia l'ultimo punto di un sotto-percorso chiuso.

### Definizione:
```python
@property
def path_types(self):
    ...
```

### Vedi anche
* classe [`ShapeElement`](/slides/python-net/it/aspose.slides/shapeelement)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)