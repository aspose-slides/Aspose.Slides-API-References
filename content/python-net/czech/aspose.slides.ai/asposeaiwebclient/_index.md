---
title: AsposeAIWebClient class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient třída

Vestavěná implementace [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient), která se připojuje k vlastnímu LLM společnosti Aspose.  
Jedná se o výchozí klient, který používá konstruktor **SlidesAIAgent.#ctor** bez parametrů.

Typ AsposeAIWebClient poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient/__init__/#) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k výchozímu koncovému bodu Aspose LLM.<br/>            Jedná se o klienta používaného konstruktor **SlidesAIAgent.#ctor** bez parametrů, takže jeho explicitní vytvoření je potřeba pouze při předávání klienta do konstruktoru **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            přímo. |
| [`__init__(self, url)`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Vytvoří instanci Aspose AI webového klienta, který se připojuje k vlastnímu koncovému bodu URL. Použijte toto<br/>            přetížení, pokud máte URL poskytnuté týmem Aspose.Slides; jinak použijte<br/>            přetížení **AsposeAIWebClient.#ctor** s výchozí URL. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Vytvoří instanci konverzace. Na rozdíl od běžných volání AI si konverzace uchovávají celý kontext. |

### Viz také
* třída [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)