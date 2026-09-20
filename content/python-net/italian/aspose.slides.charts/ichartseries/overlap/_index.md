---
title: overlap property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## Overlap proprietà
Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). 
            Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre. 
            È una proiezione della proprietà appropriata nel gruppo di serie padre, e quindi questa proprietà è di sola lettura.
            Per modificare il valore, utilizzare la proprietà di lettura/scrittura ParentSeriesGroup.Overlap.
            Solo lettura **int**.


### Note

Overlap specifica il grado di sovrapposizione o spaziatura tra le barre e le colonne come percentuale della loro larghezza:
            - -100%: Spaziatura massima (le barre sono completamente separate).
            - 0%: Le barre sono posizionate affiancate senza sovrapposizione o spaziatura.
            - 100%: Sovrapposizione massima (le barre si sovrappongono completamente).
            Questa è una proiezione della proprietà ParentSeriesGroup.Overlap.

### Definizione:
```python
@property
def overlap(self):
    ...
```


### Vedi anche
* classe [`IChartSeries`](/slides/python-net/it/aspose.slides.charts/ichartseries)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)