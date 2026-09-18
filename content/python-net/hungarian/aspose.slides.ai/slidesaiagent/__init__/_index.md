---
title: SlidesAIAgent constructor
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Inicializál egy új példányt a(z) [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent) osztályból a beépített [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient) alapértelmezett konfigurációval. A kliens az Aspose saját LLM-jéhez csatlakozik, és nem igényel további konfigurációt. Ha más AI klienst szeretne használni, akkor a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload-et használja helyette.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Inicializál egy új példányt a(z) [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent) osztályból egy egyedi AI klienssel. Használja ezt az overload-et az AI szolgáltató megadásához, saját LLM biztosításához, vagy a kapcsolat testreszabásához (például saját `HttpClient` megadásával). Bármilyen [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítás használható, többek között:
* [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)

A beépített [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient) alapértelmezett konfigurációval való használatához használja a **SlidesAIAgent.#ctor** overload-et helyette.

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) | AI client instance. Any implementation of [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) can be used. |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI client instance is not provided. |

### Lásd még
* class [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient)
* class [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)