---
title: translate method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Tłumaczy prezentację na określony język przy użyciu AI (wersja synchroniczna).


```python
def translate(self, presentation, language):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation) | Prezentacja docelowa |
| language | **str** | Język docelowy |

### Uwagi
Przykład poniżej używa domyślnego [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient), który jest tworzony przez konstruktor **SlidesAIAgent.#ctor** bez parametrów i łączy się z własnym modelem LLM firmy Aspose. Aby użyć innego dostawcy AI, dostarcz własny model LLM lub dostosuj połączenie (na przykład, podając własny `HttpClient`), przekaż implementację [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) do konstruktora **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Dostępne implementacje to:
             
* [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation instance is not provided |
| **RuntimeError(Proxy error(ArgumentException))** | Language value can't be None or empty |



### Zobacz także
* klasa [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* klasa [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* klasa [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)
* klasa [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* klasa [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)