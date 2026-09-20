---
title: SlidesAIAgent class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent klass

Tillhandahåller AI-drivna funktioner för att bearbeta presentationer.

SlidesAIAgent-typen visar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Initierar en ny instans av [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent) med en anpassad AI-klient.<br/>            Använd den här överlagringen för att ange AI-leverantören, leverera din egen LLM, eller anpassa den<br/>            anslutningen (till exempel genom att tillhandahålla din egen `HttpClient`).<br/>            Alla implementationer av [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient) kan användas, inklusive:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            För att använda den inbyggda [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient) med dess standardkonfiguration,<br/>            använd **SlidesAIAgent.#ctor**-överlagringen istället. |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent/__init__/#) | Initierar en ny instans av [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent) med den inbyggda<br/>            [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient) med dess standardkonfiguration. Klienten ansluter till<br/>            Aspose:s egen LLM och kräver ingen ytterligare konfiguration.<br/>            För att använda en annan AI-klient, använd **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-överlagringen istället. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Skapar en presentationsinstans från en textbeskrivning. Ange ett ämne, idéer, citat eller textsnuttar på det erforderliga språket. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Skapar en presentationsinstans från en textbeskrivning. Ange ett ämne, idéer, citat eller textsnuttar på det erforderliga språket. |
| [`translate(self, presentation, language)`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Översätter en presentation till det angivna språket med hjälp av AI (synkron version). |

### Se även
* klass [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* klass [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)
* klass [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)
* klass [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* klass [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)