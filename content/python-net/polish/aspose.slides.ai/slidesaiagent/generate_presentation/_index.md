---
title: generate_presentation method
second_title: Aspose.Slides dla Pythona – odwołanie API .NET
description: 
type: docs
url: /pl/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Generuje instancję prezentacji na podstawie opisu tekstowego. Dostarcz temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| description | **str** | Temat, pomysły, cytaty lub fragmenty tekstu. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/pl/aspose.slides.ai/presentationcontentamounttype) | Ilość treści w powstałej prezentacji. |

### Uwagi

Przykład poniżej używa domyślnego [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient), który jest tworzony przez konstruktor bez parametrów **SlidesAIAgent.#ctor** i łączy się z własnym LLM firmy Aspose. Aby użyć innego dostawcy AI, dostarcz własny LLM lub dostosuj połączenie (na przykład, podając własny `HttpClient`), przekaż implementację [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) do konstruktora **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Dostępne implementacje to:
             
* [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Instrukcja czatu AI nie może być None ani pusta. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Generuje instancję prezentacji na podstawie opisu tekstowego. Dostarcz temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| description | **str** | Temat, pomysły, cytaty lub fragmenty tekstu. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/pl/aspose.slides.ai/presentationcontentamounttype) | Ilość treści w powstałej prezentacji. |
| presentation_template | [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation) | Prezentacja używana jako szablon układu i projektu, zastępująca domyślny szablon. |

### Uwagi

Przykład poniżej używa domyślnego [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient), który jest tworzony przez konstruktor bez parametrów **SlidesAIAgent.#ctor** i łączy się z własnym LLM firmy Aspose. Aby użyć innego dostawcy AI, dostarcz własny LLM lub dostosuj połączenie (na przykład, podając własny `HttpClient`), przekaż implementację [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) do konstruktora **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Dostępne implementacje to:
            
* [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Nie podano szablonu prezentacji. |
| **RuntimeError(Proxy error(ArgumentException))** | Instrukcja czatu AI nie może być None ani pusta. |



### Zobacz także
* klasa [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* klasa [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* klasa [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)
* klasa [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* enumeracja [`PresentationContentAmountType`](/slides/python-net/pl/aspose.slides.ai/presentationcontentamounttype)
* klasa [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)