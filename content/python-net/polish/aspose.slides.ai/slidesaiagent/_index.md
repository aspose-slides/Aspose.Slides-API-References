---
title: SlidesAIAgent class
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent klasa

Udostępnia funkcje oparte na sztucznej inteligencji do przetwarzania prezentacji.

Typ SlidesAIAgent udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Inicjalizuje nową instancję [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent) z własnym klientem AI.<br/>            Użyj tej przeciążonej wersji, aby określić dostawcę AI, dostarczyć własny LLM lub dostosować<br/>            połączenie (na przykład, podając własny `HttpClient`).<br/>            Każda implementacja [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) może być użyta, w tym:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Aby użyć wbudowanego [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient) z domyślną konfiguracją,<br/>            użyj przeciążenia **SlidesAIAgent.#ctor**. |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent/__init__/#) | Inicjalizuje nową instancję [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent) przy użyciu wbudowanego<br/>            [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient) z domyślną konfiguracją. Klient łączy się z<br/>            własnym LLM firmy Aspose i nie wymaga dodatkowej konfiguracji.<br/>            Aby użyć innego klienta AI, użyj przeciążenia **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Generuje instancję prezentacji na podstawie opisu tekstowego. Podaj temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Generuje instancję prezentacji na podstawie opisu tekstowego. Podaj temat, pomysły, cytaty lub fragmenty tekstu w wymaganym języku. |
| [`translate(self, presentation, language)`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Tłumaczy prezentację na określony język przy użyciu AI (wersja synchroniczna). |


### Zobacz także
* klasa [`AsposeAIWebClient`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient)
* klasa [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient)
* klasa [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)
* klasa [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* klasa [`SlidesAIAgent`](/slides/python-net/pl/aspose.slides.ai/slidesaiagent)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)