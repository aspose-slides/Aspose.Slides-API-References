---
title: aspose.slides.ai
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/
---
Bevat klassen die AI-gebaseerde functies bieden voor het analyseren en verwerken van PowerPoint-presentaties.
## Klassen

| Klasse | Beschrijving |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient/) | Een ingebouwde [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)-implementatie die verbinding maakt met de eigen LLM van Aspose.<br/>Dit is de standaardclient die wordt gebruikt door de parameterloze **SlidesAIAgent.#ctor** constructor. |
| [`IAIConversation`](/slides/python-net/nl/aspose.slides.ai/iaiconversation/) | Stelt een gesprek-instantie voor. In tegenstelling tot gewone AI-aanroepen behouden conversaties de volledige context. |
| [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient/) | AI-webclient-interface. Deze interface maakt het mogelijk om verschillende AI-taalmodellen te vervangen.<br/> Klassen die deze interface implementeren, moeten worden gebruikt in combinatie met `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient/) | Een ingebouwde [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)-implementatie die verbinding maakt met een OpenAI-compatibele LLM-provider<br/> op een opgegeven basis-URL. |
| [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient/) | Een ingebouwde [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)-implementatie die verbinding maakt met de OpenAI-API. |
| [`SlidesAIAgent`](/slides/python-net/nl/aspose.slides.ai/slidesaiagent/) | Biedt AI-aangedreven functies voor het verwerken van presentaties. |
| [`SlidesAIAgentException`](/slides/python-net/nl/aspose.slides.ai/slidesaiagentexception/) | Stelt gerelateerde uitzonderingen van Slides AI Agent voor. |

## Enumeraties

| Enumeratie | Beschrijving |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/nl/aspose.slides.ai/presentationcontentamounttype/) | Specificeert de hoeveelheid inhoud die in de gegenereerde presentatie is opgenomen, wat zowel het aantal dia's als het detailniveau per dia beïnvloedt. |