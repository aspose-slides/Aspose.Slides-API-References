---
title: set_metered_key method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Imposta le chiavi pubblica e privata a consumo.
            Se acquisti una licenza a consumo, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente, questo è sufficiente. 
            Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata in stato di valutazione, 
            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API.

```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| public_key | **str** | chiave pubblica |
| private_key | **str** | chiave privata |



### Vedi anche
* classe [`Metered`](/slides/python-net/it/aspose.slides/metered)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)