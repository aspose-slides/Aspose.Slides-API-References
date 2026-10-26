---
title: SlidesAIAgent class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent classe

Fornisce funzionalità basate sull'IA per l'elaborazione delle presentazioni.

Il tipo SlidesAIAgent espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/it/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Inizializza una nuova istanza di [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent) con un client IA personalizzato.<br/>            Usa questa overload per specificare il provider IA, fornire il tuo LLM, o personalizzare la<br/>            connessione (ad esempio, fornendo il tuo `HttpClient`).<br/>            È possibile utilizzare qualsiasi implementazione di [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient), inclusa:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Per utilizzare il [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient) integrato con la sua configurazione predefinita,<br/>            usa l'overload **SlidesAIAgent.#ctor** invece. |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.ai/slidesaiagent/__init__/#) | Inizializza una nuova istanza di [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent) utilizzando il [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient) integrato con la sua configurazione predefinita. Il client si connette al LLM di Aspose e non richiede configurazioni aggiuntive.<br/>            Per utilizzare un client IA diverso, usa l'overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** invece. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/it/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Genera un'istanza di presentazione da una descrizione testuale. Fornisci un argomento, idee, citazioni o frammenti di testo nella lingua richiesta. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/it/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Genera un'istanza di presentazione da una descrizione testuale. Fornisci un argomento, idee, citazioni o frammenti di testo nella lingua richiesta. |
| [`translate(self, presentation, language)`](/slides/python-net/it/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Traduce una presentazione nella lingua specificata usando l'IA (versione sincrona). |

### Vedi anche
* classe [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)