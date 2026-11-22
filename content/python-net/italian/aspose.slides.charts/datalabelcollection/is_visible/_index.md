---
title: is_visible property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelcollection/is_visible/
weight: 130
---
## proprietà is_visible
False significa che l'etichetta di dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false).
            Sola lettura **bool**.


### Osservazioni

Se l'etichetta di dati è visibile per impostazione predefinita, è possibile renderla nascosta per impostazione predefinita con il metodo Hide().
            Ma se l'etichetta di dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l'etichetta di dati "visibile per impostazione predefinita" impostando i flag Show*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat
            su true.

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