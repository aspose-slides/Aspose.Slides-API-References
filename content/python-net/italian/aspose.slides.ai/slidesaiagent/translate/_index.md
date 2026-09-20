---
title: translate method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Traduce una presentazione nella lingua specificata usando l'IA (versione sincrona).


```python
def translate(self, presentation, language):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) | Presentazione di destinazione |
| language | **str** | Lingua di destinazione |

### Osservazioni

L'esempio seguente utilizza il predefinito [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient), che è creato dal costruttore **SlidesAIAgent.#ctor** senza parametri e si collega al LLM di Aspose. Per utilizzare un provider AI diverso, fornire il proprio LLM o personalizzare la connessione (ad esempio, fornendo il proprio `HttpClient`), passare un'implementazione [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) al costruttore **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Le implementazioni disponibili includono:
             
* [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'istanza della presentazione non è fornita |
| **RuntimeError(Proxy error(ArgumentException))** | Il valore della lingua non può essere None o vuoto |



### Vedi anche
* classe [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)