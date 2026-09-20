---
title: OpenAIWebClient constructor
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Crea un'istanza del client web OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| model | **str** | Modello di linguaggio OpenAI. Valori possibili:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API key. |
| organization_id | **str** | Organization ID (opzionale). |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Il valore della API key non può essere None o vuoto. |
| **RuntimeError(Proxy error(ArgumentException))** | Il valore del modello di testo non può essere None o vuoto. |



### Vedi anche
* classe [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)