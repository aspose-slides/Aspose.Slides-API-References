---
title: translate method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Vertaal een presentatie naar de opgegeven taal met behulp van AI (synchrone versie).


```python
def translate(self, presentation, language):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) | Doelpresentatie |
| language | **str** | Doeltaal |

### Opmerkingen

Het onderstaande voorbeeld gebruikt de standaard [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient), die wordt aangemaakt door de parameterloze **SlidesAIAgent.#ctor**-constructor en verbindt met de eigen LLM van Aspose. Om een andere AI-provider te gebruiken, lever uw eigen LLM, of pas de verbinding aan (bijvoorbeeld door uw eigen `HttpClient` te leveren), geef een [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)-implementatie door aan de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-constructor. Beschikbare implementaties zijn:
             
* [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentatie-instantie is niet opgegeven |
| **RuntimeError(Proxy error(ArgumentException))** | Taalwaarde mag niet None of leeg zijn |



### Zie ook
* klasse [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* klasse [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* klasse [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)
* klasse [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* klasse [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* bibliotheek [`Aspose.Slides`](/slides/python-net)