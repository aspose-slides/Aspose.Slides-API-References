---
title: is_visible property
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelcollection/is_visible/
weight: 120
---
## is_visible proprietà
False indica che l’etichetta dei dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false).
            Sola lettura **bool**.

### Osservazioni

Se l’etichetta dei dati è visibile per impostazione predefinita, è possibile nasconderla per impostazione predefinita con il metodo Hide().
            Ma se l’etichetta dei dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l’etichetta dei dati "visibile per impostazione predefinita" impostando i flag Show*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato true.

### Definizione:
```python
@property
def is_visible(self):
    ...
```

### Vedi anche
* classe [`DataLabelCollection`](/slides/python-net/it/aspose.slides.charts/datalabelcollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)