---
title: set_embedded_data method
second_title: Aspose.Slides per Python via Riferimento API .NET
description: 
type: docs
url: /it/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Imposta le informazioni sui dati OLE incorporati.

```python
def set_embedded_data(self, embedded_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo) | Dati incorporati [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo) |

### Note

Questo metodo modifica le proprietà dell'oggetto per riflettere i nuovi dati e imposta il flag IsObjectLink su false, indicando che l'oggetto OLE è incorporato.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando il parametro embeddedData è None. |

### Vedi anche
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)