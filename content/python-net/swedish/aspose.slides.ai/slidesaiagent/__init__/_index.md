---
title: SlidesAIAgent constructor
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Skapar en ny instans av [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent) med den inbyggda
[`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient) med dess standardkonfiguration. Klienten ansluter till
Asposes egna LLM och kräver ingen ytterligare konfiguration.
För att använda en annan AI-klient, använd **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload istället.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Skapar en ny instans av [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent) med en anpassad AI-klient. Använd denna overload för att ange AI-leverantören, leverera din egen LLM eller anpassa anslutningen (till exempel genom att tillhandahålla din egen `HttpClient`). Alla implementationer av [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient) kan användas, inklusive:

* [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)

För att använda den inbyggda [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient) med dess standardkonfiguration,
använd **SlidesAIAgent.#ctor** overload istället.

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient) | AI-klientinstans. Alla implementationer av [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient) kan användas. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI-klientinstans har inte tillhandahållits. |

### Se även
* klass [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* klass [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)
* klass [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)
* klass [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* klass [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* bibliotek [`Aspose.Slides`](/slides/python-net)