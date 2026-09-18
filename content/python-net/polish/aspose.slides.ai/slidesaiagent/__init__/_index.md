---
title: SlidesAIAgent constructor
second_title: Aspose.Slides dla Pythona przy użyciu .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Inicjalizuje nową instancję [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent) przy użyciu wbudowanego
[`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient) z domyślną konfiguracją. Klient łączy się z
LLM firmy Aspose i nie wymaga dodatkowej konfiguracji.
Aby użyć innego klienta AI, użyj przeciążenia **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**.

```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
Inicjalizuje nową instancję [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent) z własnym klientem AI.
Użyj tego przeciążenia, aby określić dostawcę AI, dostarczyć własny LLM lub dostosować
połączenie (na przykład, podając własny `HttpClient`).
Można użyć dowolnej implementacji [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient), w tym:
            
* [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)


Aby użyć wbudowanego [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient) z jego domyślną konfiguracją,
użyj przeciążenia **SlidesAIAgent.#ctor**.

```python
def __init__(self, ai_client):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) | Instancja klienta AI. Można użyć dowolnej implementacji [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Instancja klienta AI nie została podana. |



### Zobacz także
* klasa [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* klasa [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient)
* klasa [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)
* klasa [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* klasa [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)