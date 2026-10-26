---
title: SlidesAIAgent constructor
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Inizializza una nuova istanza di [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent) utilizzando il [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient) integrato con la sua configurazione predefinita. Il client si connette al LLM di Aspose e non richiede configurazioni aggiuntive. Per utilizzare un client AI diverso, usa il sovraccarico **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**.

```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
Inizializza una nuova istanza di [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent) con un client AI personalizzato. Usa questo sovraccarico per specificare il provider AI, fornire il tuo LLM o personalizzare la connessione (ad esempio, fornendo il tuo `HttpClient`). È possibile utilizzare qualsiasi implementazione di [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient), inclusa:
            
* [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)


Per utilizzare il [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient) integrato con la sua configurazione predefinita, usa il sovraccarico **SlidesAIAgent.#ctor**.

```python
def __init__(self, ai_client):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) | Istanza del client AI. È possibile utilizzare qualsiasi implementazione di [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'istanza del client AI non è fornita. |



### Vedi anche
* classe [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)