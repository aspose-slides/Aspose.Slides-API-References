---
title: overlap property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## proprietà overlap
Specifica quanto le barre e le colonne si sovrappongono nei grafici 2-D, come percentuale (da -100% a 100%). 
            Questa è la proprietà non solo di questa serie ma di tutte le serie del gruppo di serie padre. 
            È una proiezione della proprietà appropriata nel gruppo di serie padre, quindi questa proprietà è solo lettura.
            Per modificare il valore, utilizza la proprietà **ParentSeriesGroup.Overlap** di lettura/scrittura.
            Solo lettura **int**.


### Osservazioni

Overlap specifica il grado di sovrapposizione o spaziatura tra barre e colonne come percentuale della loro larghezza:
            - -100%: Spaziatura massima (le barre sono completamente separate).
            - 0%: Le barre sono posizionate una accanto all'altra senza sovrapposizione né spaziatura.
            - 100%: Sovrapposizione massima (le barre si sovrappongono completamente).
            Questa è una proiezione della proprietà **ParentSeriesGroup.Overlap**.

### Definizione:
```python
@property
def overlap(self):
    ...
```


### Vedi anche
* classe [`ChartSeries`](/slides/python-net/it/aspose.slides.charts/chartseries)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)