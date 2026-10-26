---
title: aspose.slides.ai
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/
---
Innehåller klasser som tillhandahåller AI-baserade funktioner för att analysera och bearbeta PowerPoint-presentationer.
## Klasser

| Klass | Beskrivning |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient/) | En inbyggd [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)-implementation som ansluter till Asposes egen LLM.<br/>            Detta är standardklienten som används av den parameterlösa **SlidesAIAgent.#ctor**-konstruktorn. |
| [`IAIConversation`](/slides/python-net/sv/aspose.slides.ai/iaiconversation/) | Representerar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten. |
| [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient/) | AI Web-klientgränssnitt. Detta gränssnitt möjliggör att ersätta olika AI-språkmodeller.<br/>            Klasser som implementerar detta gränssnitt bör användas tillsammans med `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient/) | En inbyggd [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)-implementation som ansluter till en OpenAI-kompatibel LLM-leverantör<br/>            på en angiven bas-URL. |
| [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient/) | En inbyggd [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)-implementation som ansluter till OpenAI API. |
| [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent/) | Tillhandahåller AI-drivna funktioner för att bearbeta presentationer. |
| [`SlidesAIAgentException`](/slides/python-net/sv/aspose.slides.ai/slidesaiagentexception/) | Representerar undantag relaterade till Slides AI Agent. |

## Uppräkningar

| Uppräkning | Beskrivning |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/sv/aspose.slides.ai/presentationcontentamounttype/) | Anger mängden innehåll som inkluderas i den genererade presentationen, vilket påverkar både antalet bilder och detaljnivån per bild. |