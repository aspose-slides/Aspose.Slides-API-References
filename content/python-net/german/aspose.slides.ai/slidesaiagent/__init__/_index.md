---
title: SlidesAIAgent constructor
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Initialisiert eine neue Instanz von [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent) mit dem integrierten [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient) und seiner Standardkonfiguration. Der Client verbindet sich mit Asposes eigenem LLM und erfordert keine zusätzliche Konfiguration. Um einen anderen KI-Client zu verwenden, benutzen Sie die **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** Überladung stattdessen.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Initialisiert eine neue Instanz von [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent) mit einem benutzerdefinierten KI-Client. Verwenden Sie diese Überladung, um den KI-Anbieter anzugeben, Ihr eigenes LLM bereitzustellen oder die Verbindung anzupassen (zum Beispiel, indem Sie Ihren eigenen `HttpClient` bereitstellen). Jede Implementierung von [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient) kann verwendet werden, einschließlich:

* [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)

Um das integrierte [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient) mit seiner Standardkonfiguration zu verwenden, benutzen Sie stattdessen die **SlidesAIAgent.#ctor** Überladung.

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient) | KI-Client-Instanz. Jede Implementierung von [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient) kann verwendet werden. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | KI-Client-Instanz wurde nicht bereitgestellt. |

### Siehe auch
* Klasse [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* Klasse [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)
* Klasse [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)
* Klasse [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* Klasse [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)