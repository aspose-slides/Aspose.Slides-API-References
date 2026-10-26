---
title: SlidesAIAgent constructor
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Initialiseert een nieuw exemplaar van [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent) met de ingebouwde [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient) en de standaardconfiguratie. De client maakt verbinding met de eigen LLM van Aspose en vereist geen extra configuratie. Gebruik een andere AI-client door de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload te gebruiken.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Initialiseert een nieuw exemplaar van [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent) met een aangepaste AI-client. Gebruik deze overload om de AI-provider op te geven, uw eigen LLM te leveren, of de verbinding aan te passen (bijvoorbeeld door uw eigen `HttpClient` te verstrekken). Elke implementatie van [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient) kan worden gebruikt, inclusief:
* [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)

Om de ingebouwde [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient) met de standaardconfiguratie te gebruiken, gebruik de **SlidesAIAgent.#ctor** overload.

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient) | AI-clientinstantie. Elke implementatie van [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient) kan worden gebruikt. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI-clientinstantie is niet opgegeven. |

### Zie ook
* klasse [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* klasse [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)
* klasse [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)
* klasse [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* klasse [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* bibliotheek [`Aspose.Slides`](/slides/python-net)