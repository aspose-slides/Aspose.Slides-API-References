---
title: SlidesAIAgent class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent Klasse

Bietet KI-gestützte Funktionen zur Verarbeitung von Präsentationen.

Der SlidesAIAgent-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/de/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Initialisiert eine neue Instanz von [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent) mit einem benutzerdefinierten KI-Client.<br/>            Verwenden Sie diese Überladung, um den KI-Anbieter anzugeben, Ihr eigenes LLM bereitzustellen oder die Verbindung anzupassen (zum Beispiel, indem Sie Ihren eigenen `HttpClient` bereitstellen).<br/>            Jede Implementierung von [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient) kann verwendet werden, einschließlich:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Um das integrierte [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient) mit seiner Standardkonfiguration zu verwenden,<br/>            nutzen Sie stattdessen die **SlidesAIAgent.#ctor**-Überladung. |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.ai/slidesaiagent/__init__/#) | Initialisiert eine neue Instanz von [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent) unter Verwendung des integrierten<br/>            [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient) mit seiner Standardkonfiguration. Der Client stellt eine Verbindung zu<br/>            Asposes eigenem LLM her und erfordert keine zusätzliche Konfiguration.<br/>            Um einen anderen KI-Client zu verwenden, nutzen Sie stattdessen die **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-Überladung. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/de/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Generiert eine Präsentationsinstanz aus einer Textbeschreibung. Geben Sie ein Thema, Ideen, Zitate oder Textausschnitte in der gewünschten Sprache an. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/de/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Generiert eine Präsentationsinstanz aus einer Textbeschreibung. Geben Sie ein Thema, Ideen, Zitate oder Textausschnitte in der gewünschten Sprache an. |
| [`translate(self, presentation, language)`](/slides/python-net/de/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Übersetzt eine Präsentation in die angegebene Sprache mithilfe von KI (synchrone Version). |


### Siehe auch
* Klasse [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* Klasse [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)
* Klasse [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)
* Klasse [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* Klasse [`SlidesAIAgent`](/slides/python-net/de/aspose.slides.ai/slidesaiagent)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)