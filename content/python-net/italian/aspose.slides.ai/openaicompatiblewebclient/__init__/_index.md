---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Crea un'istanza del client web compatibile con OpenAI.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| model | **str** | Nome del modello supportato dal provider LLM. |
| api_key | **str** | Chiave API (token). |
| base_url | **str** | URL di base del LLM compatibile con OpenAI. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Il valore della chiave API non può essere None o vuoto. |
| **RuntimeError(Proxy error(ArgumentException))** | Il valore del modello di testo non può essere None o vuoto. |
| **RuntimeError(Proxy error(ArgumentException))** | Il valore dell'URL di base non può essere None o vuoto. |



### Vedi anche
* classe [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)