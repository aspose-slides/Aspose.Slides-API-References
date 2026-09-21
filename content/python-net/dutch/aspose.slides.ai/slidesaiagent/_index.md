---
title: SlidesAIAgent class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent klasse

Biedt AI-ondersteunde functies voor het verwerken van presentaties.

Het SlidesAIAgent-type maakt de volgende leden beschikbaar:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Initialiseert een nieuwe instantie van [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent) met een aangepaste AI-client.<br/>            Gebruik deze overload om de AI-provider op te geven, uw eigen LLM te leveren, of de<br/>            verbinding aan te passen (bijvoorbeeld door uw eigen `HttpClient` te verstrekken).<br/>            Elke implementatie van [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient) kan worden gebruikt, inclusief:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Om de ingebouwde [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient) met de standaardconfiguratie te gebruiken,<br/>            gebruik dan de **SlidesAIAgent.#ctor** overload. |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent/__init__/#) | Initialiseert een nieuwe instantie van [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent) met gebruik van de ingebouwde<br/>            [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient) met de standaardconfiguratie. De client maakt verbinding met<br/>            de eigen LLM van Aspose en vereist geen extra configuratie.<br/>            Om een andere AI-client te gebruiken, gebruik dan de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Genereert een presentatie-instantie op basis van een tekstbeschrijving. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de vereiste taal. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Genereert een presentatie-instantie op basis van een tekstbeschrijving. Geef een onderwerp, ideeën, citaten of tekstfragmenten op in de vereiste taal. |
| [`translate(self, presentation, language)`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Vertalt een presentatie naar de opgegeven taal met behulp van AI (synchrone versie). |


### Zie ook
* klasse [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* klasse [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)
* klasse [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)
* klasse [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* klasse [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* bibliotheek [`Aspose.Slides`](/slides/python-net)