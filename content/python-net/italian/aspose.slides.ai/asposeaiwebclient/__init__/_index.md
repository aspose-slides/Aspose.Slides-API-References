---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito di Aspose LLM.
            Questo è il client utilizzato dal costruttore senza parametri **SlidesAIAgent.#ctor**, quindi creando
            esplicitamente è necessario solo quando si passa il client al **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**
            costruttore direttamente.

```python
def __init__(self):
    ...
```

## __init__(self, url) {#str}
Crea un'istanza del client web Aspose AI che si connette a un URL di endpoint personalizzato. Usa questo
            sovraccarico quando disponi di un URL fornito dal team Aspose.Slides; altrimenti, usa il
            sovraccarico **AsposeAIWebClient.#ctor** con l'URL predefinito.

```python
def __init__(self, url):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| url | **str** | URL dell'endpoint di Aspose LLM, fornito dal team Aspose.Slides. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'URL non può essere None o vuoto. |

### Vedi anche
* classe [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)