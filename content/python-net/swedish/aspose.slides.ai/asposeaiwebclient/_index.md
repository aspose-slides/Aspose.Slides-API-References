---
title: AsposeAIWebClient class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient klass

En inbyggd [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient) implementation som ansluter till Asposes egen LLM.  
Det här är standardklienten som används av den parameterlösa **SlidesAIAgent.#ctor** konstruktorn.

Typen AsposeAIWebClient exponerar följande medlemmar:

## Konstruktörer

| Konstruktör | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient/__init__/#) | Skapar en instans av Aspose AI-webbklienten som ansluter till standard-Aspose LLM-slutpunkten.<br/>Detta är klienten som används av den parameterlösa **SlidesAIAgent.#ctor** konstruktorn, så att skapa den explicit endast krävs när man vidarebefordrar klienten till **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>konstruktorn direkt. |
| [`__init__(self, url)`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Skapar en instans av Aspose AI-webbklienten som ansluter till en anpassad slutpunkts-URL. Använd detta<br/>överlagring när du har en URL som tillhandahålls av Aspose.Slides-teamet; annars, använd<br/>**AsposeAIWebClient.#ctor** överlagring med standard-URL:en. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Skapar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela sammanhanget. |

### Se också
* klass [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* bibliotek [`Aspose.Slides`](/slides/python-net)