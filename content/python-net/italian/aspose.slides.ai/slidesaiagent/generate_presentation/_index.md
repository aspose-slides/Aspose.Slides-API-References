---
title: generate_presentation method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Genera un'istanza di presentazione da una descrizione testuale. Fornisci un argomento, idee, citazioni o frammenti di testo nella lingua richiesta.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| description | **str** | L'argomento, le idee, le citazioni o i frammenti di testo. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/it/aspose.slides.ai/presentationcontentamounttype) | La quantità di contenuto nella presentazione risultante. |

### Osservazioni

L'esempio seguente utilizza il valore predefinito [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient), che è creato dal costruttore senza parametri **SlidesAIAgent.#ctor** e si connette al LLM proprietario di Aspose. Per utilizzare un fornitore di IA diverso, fornisci il tuo LLM o personalizza la connessione (ad esempio, fornendo il tuo `HttpClient`), passando un'implementazione [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) al costruttore **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Le implementazioni disponibili includono:

* [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | L'istruzione della chat AI non può essere None o vuota. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Genera un'istanza di presentazione da una descrizione testuale. Fornisci un argomento, idee, citazioni o frammenti di testo nella lingua richiesta.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| description | **str** | L'argomento, le idee, le citazioni o i frammenti di testo. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/it/aspose.slides.ai/presentationcontentamounttype) | La quantità di contenuto nella presentazione risultante. |
| presentation_template | [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) | Una presentazione da usare come modello per layout e design, sostituendo il modello predefinito. |

### Osservazioni

L'esempio seguente utilizza il valore predefinito [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient), che è creato dal costruttore senza parametri **SlidesAIAgent.#ctor** e si connette al LLM proprietario di Aspose. Per utilizzare un fornitore di IA diverso, fornisci il tuo LLM o personalizza la connessione (ad esempio, fornendo il tuo `HttpClient`), passando un'implementazione [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) al costruttore **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Le implementazioni disponibili includono:

* [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Il modello di presentazione non è stato fornito. |
| **RuntimeError(Proxy error(ArgumentException))** | L'istruzione della chat AI non può essere None o vuota. |

### Vedi anche
* classe [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* enumerazione [`PresentationContentAmountType`](/slides/python-net/it/aspose.slides.ai/presentationcontentamounttype)
* classe [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)