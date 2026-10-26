---
title: generate_presentation method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Genereert een presentatie-instantie op basis van een tekstopmaak. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de vereiste taal.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| description | **str** | Het onderwerp, ideeën, citaten of tekstfragmenten. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/nl/aspose.slides.ai/presentationcontentamounttype) | De hoeveelheid inhoud in de resulterende presentatie. |

### Opmerkingen

Het onderstaande voorbeeld gebruikt de standaard [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient), die wordt aangemaakt door de parameterloze **SlidesAIAgent.#ctor** constructor en verbinding maakt met de eigen LLM van Aspose. Om een andere AI-provider te gebruiken, lever uw eigen LLM, of pas de verbinding aan (bijvoorbeeld door uw eigen `HttpClient` te leveren), geef een [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)-implementatie door aan de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** constructor. Beschikbare implementaties omvatten:

* [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI-chatinstructie mag niet None of leeg zijn. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Genereert een presentatie-instantie op basis van een tekstopmaak. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de vereiste taal.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| description | **str** | Het onderwerp, ideeën, citaten of tekstfragmenten. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/nl/aspose.slides.ai/presentationcontentamounttype) | De hoeveelheid inhoud in de resulterende presentatie. |
| presentation_template | [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) | Een presentatie die wordt gebruikt als sjabloon voor lay-out en ontwerp, ter vervanging van het standaard sjabloon. |

### Opmerkingen

Het onderstaande voorbeeld gebruikt de standaard [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient), die wordt aangemaakt door de parameterloze **SlidesAIAgent.#ctor** constructor en verbinding maakt met de eigen LLM van Aspose. Om een andere AI-provider te gebruiken, lever uw eigen LLM, of pas de verbinding aan (bijvoorbeeld door uw eigen `HttpClient` te leveren), geef een [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)-implementatie door aan de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** constructor. Beschikbare implementaties omvatten:

* [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentatiesjabloon is niet opgegeven. |
| **RuntimeError(Proxy error(ArgumentException))** | AI-chatinstructie mag niet None of leeg zijn. |

### Zie ook
* class [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)
* class [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* class [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* enumeration [`PresentationContentAmountType`](/slides/python-net/nl/aspose.slides.ai/presentationcontentamounttype)
* class [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)