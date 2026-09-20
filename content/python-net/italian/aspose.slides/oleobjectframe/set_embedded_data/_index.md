---
title: set_embedded_data method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/oleobjectframe/set_embedded_data/
weight: 60
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Imposta le informazioni sui dati OLE incorporati.
            
            Questo metodo modifica le proprietà dell'oggetto per riflettere i nuovi dati e imposta il flag IsObjectLink su false, indicando che l'oggetto OLE è incorporato.


```python
def set_embedded_data(self, embedded_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo) | Dati incorporati [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo) |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando il parametro embeddedData è None. |

### Vedi anche
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo)
* classe [`OleObjectFrame`](/slides/python-net/it/aspose.slides/oleobjectframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)