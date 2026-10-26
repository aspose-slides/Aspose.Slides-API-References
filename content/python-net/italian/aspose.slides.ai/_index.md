---
title: aspose.slides.ai
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.ai/
---
Contiene classi che forniscono funzionalità basate sull'IA per l'analisi e l'elaborazione di presentazioni PowerPoint.
## Classi

| Classe | Descrizione |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/it/aspose.slides.ai/asposeaiwebclient/) | Un'implementazione integrata [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) che si connette al LLM di Aspose.<br/>            Questo è il client predefinito utilizzato dal costruttore senza parametri **SlidesAIAgent.#ctor**. |
| [`IAIConversation`](/slides/python-net/it/aspose.slides.ai/iaiconversation/) | Rappresenta un'istanza di conversazione. A differenza delle chiamate AI regolari, le conversazioni mantengono l'intero contesto. |
| [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient/) | Interfaccia client AI Web. Questa interfaccia consente di sostituire diversi modelli di linguaggio AI.<br/>            Le classi che implementano questa interfaccia devono essere utilizzate insieme a `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/it/aspose.slides.ai/openaicompatiblewebclient/) | Un'implementazione integrata [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) che si connette a un provider LLM compatibile con OpenAI<br/>            a un URL di base specificato. |
| [`OpenAIWebClient`](/slides/python-net/it/aspose.slides.ai/openaiwebclient/) | Un'implementazione integrata [`IAIWebClient`](/slides/python-net/it/aspose.slides.ai/iaiwebclient) che si connette all'API OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/it/aspose.slides.ai/slidesaiagent/) | Fornisce funzionalità basate sull'IA per l'elaborazione di presentazioni. |
| [`SlidesAIAgentException`](/slides/python-net/it/aspose.slides.ai/slidesaiagentexception/) | Rappresenta le eccezioni relative a Slides AI Agent. |

## Enumerazioni

| Enumerazione | Descrizione |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/it/aspose.slides.ai/presentationcontentamounttype/) | Specifica la quantità di contenuto inclusa nella presentazione generata, influenzando sia il numero di diapositive sia il livello di dettaglio per diapositiva. |