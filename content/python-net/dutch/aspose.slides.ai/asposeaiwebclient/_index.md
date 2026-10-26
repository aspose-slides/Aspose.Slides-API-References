---
title: AsposeAIWebClient class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient klasse

Een ingebouwde [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient) implementatie die verbinding maakt met Aspose's eigen LLM.
            Dit is de standaardclient die wordt gebruikt door de parameterloze **SlidesAIAgent.#ctor** constructor.

The AsposeAIWebClient type exposes the following members:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient/__init__/#) | Maakt een instantie van de Aspose AI webclient die verbinding maakt met het standaard Aspose LLM-endpoint.<br/>            Dit is de client die wordt gebruikt door de parameterloze **SlidesAIAgent.#ctor** constructor, dus het expliciet aanmaken<br/>            is alleen vereist wanneer de client wordt doorgegeven aan de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            constructor rechtstreeks. |
| [`__init__(self, url)`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Maakt een instantie van de Aspose AI webclient die verbinding maakt met een aangepaste endpoint-URL. Gebruik deze<br/>            overload wanneer je een URL hebt die door het Aspose.Slides-team wordt geleverd; gebruik anders de<br/>            **AsposeAIWebClient.#ctor** overload met de standaard-URL. |

## Methods

| Method | Beschrijving |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Maakt een gespreks-instantie aan. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context. |


### Zie ook
* klasse [`IAIWebClient`](/slides/python-net/nl/aspose.slides.ai/iaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* bibliotheek [`Aspose.Slides`](/slides/python-net)