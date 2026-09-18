---
title: AsposeAIWebClient class
second_title: Aspose.Slides dla Pythona poprzez .NET API
description: 
type: docs
url: /pl/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient klasa

Wbudowana [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient) implementacja łącząca się z własnym LLM firmy Aspose.  
            To jest domyślny klient używany przez konstruktor **SlidesAIAgent.#ctor** bez parametrów.

Typ AsposeAIWebClient udostępnia następujące elementy:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient/__init__/#) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z domyślnym punktem końcowym Aspose LLM.<br/>            To jest klient używany przez konstruktor **SlidesAIAgent.#ctor** bez parametrów, więc tworzenie<br/>            go jawnie jest wymagane tylko przy przekazywaniu klienta do konstruktora **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            bezpośrednio. |
| [`__init__(self, url)`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Tworzy instancję klienta sieciowego Aspose AI, który łączy się z niestandardowym adresem URL punktu końcowego. Użyj tej<br/>            przeciążonej wersji, gdy masz URL dostarczony przez zespół Aspose.Slides; w przeciwnym razie użyj<br/>            przeciążenia **AsposeAIWebClient.#ctor** z domyślnym URL. |

## Metody

| Method | Description |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/pl/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Tworzy instancję konwersacji. W przeciwieństwie do zwykłych wywołań AI, konwersacje zachowują cały kontekst. |


### Zobacz także
* klasa [`IAIWebClient`](/slides/python-net/pl/aspose.slides.ai/iaiwebclient)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)