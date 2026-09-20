---
title: SlidesAIAgent class
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent třída

Poskytuje funkce podporované AI pro zpracování prezentací.

Typ SlidesAIAgent vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Inicializuje novou instanci [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent) s vlastním AI klientem.<br/>            Použijte toto přetížení k určení poskytovatele AI, dodat vlastní LLM nebo přizpůsobit<br/>            spojení (například poskytnutím vlastního `HttpClient`).<br/>            Lze použít libovolnou implementaci [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient), včetně:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Pro použití vestavěného [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient) s jeho výchozí konfigurací,<br/>            použijte přetížení **SlidesAIAgent.#ctor** místo toho. |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent/__init__/#) | Inicializuje novou instanci [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent) pomocí vestavěného<br/>            [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient) s jeho výchozí konfigurací. Klient se připojuje k<br/>            vlastním LLM společnosti Aspose a nevyžaduje žádnou další konfiguraci.<br/>            Pro použití jiného AI klienta použijte přetížení **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** místo toho. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Vytvoří instanci prezentace z textového popisu. Poskytněte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Vytvoří instanci prezentace z textového popisu. Poskytněte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce. |
| [`translate(self, presentation, language)`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Přeloží prezentaci do zadaného jazyka pomocí AI (synchronní verze). |

### Viz také
* třída [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* třída [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient)
* třída [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)
* třída [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* třída [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)