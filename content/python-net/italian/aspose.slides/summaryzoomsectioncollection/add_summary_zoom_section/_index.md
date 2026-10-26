---
title: add_summary_zoom_section method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
Crea un nuovo oggetto Summary Zoom Section e lo aggiunge alla collezione

### Restituisce

Elemento [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe) aggiunto



```python
def add_summary_zoom_section(self, section):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Sezione per un nuovo elemento Summary Zoom Section [`ISection`](/slides/python-net/it/aspose.slides/isection) |

### Osservazioni

Se un elemento per questa sezione esiste già nella collezione, viene restituito l'elemento esistente.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | La sezione di riferimento non appartiene alla presentazione corrente o non contiene alcuna diapositiva. |



### Vedi anche
* classe [`ISection`](/slides/python-net/it/aspose.slides/isection)
* classe [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe)
* classe [`ISummaryZoomSection`](/slides/python-net/it/aspose.slides/isummaryzoomsection)
* classe [`SummaryZoomSectionCollection`](/slides/python-net/it/aspose.slides/summaryzoomsectioncollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)