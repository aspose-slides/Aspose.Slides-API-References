---
title: AsposeAIWebClient class
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient classe

Un'implementazione [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) integrata che si connette al LLM proprietario di Aspose. Questo è il client predefinito usato dal costruttore senza parametri **SlidesAIAgent.#ctor**.

Il tipo AsposeAIWebClient espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient/__init__/#) | Crea un'istanza del client web Aspose AI che si connette all'endpoint predefinito del LLM di Aspose.<br/>            Questo è il client usato dal costruttore senza parametri **SlidesAIAgent.#ctor**, quindi crearne<br/>            esplicitamente è necessario solo quando si passa il client al costruttore **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            direttamente. |
| [`__init__(self, url)`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Crea un'istanza del client web Aspose AI che si connette a un URL di endpoint personalizzato. Usa questo<br/>            overload quando disponi di un URL fornito dal team Aspose.Slides; altrimenti, usa il<br/>            overload **AsposeAIWebClient.#ctor** con l'URL predefinito. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Crea un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni mantengono l'intero contesto. |

### Vedi anche
* classe [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient)
* modulo [`aspose.slides.ai`](/slides/python-net/it/aspose.slides.ai)
* libreria [`Aspose.Slides`](/slides/python-net)