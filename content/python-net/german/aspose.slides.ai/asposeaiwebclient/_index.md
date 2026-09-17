---
title: AsposeAIWebClient class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient Klasse

Eine integrierte [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)-Implementierung, die eine Verbindung zum eigenen LLM von Aspose herstellt.
            Dies ist der Standard-Client, der vom parameterlosen **SlidesAIAgent.#ctor**-Konstruktor verwendet wird.

Der AsposeAIWebClient-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient/__init__/#) | Erstellt eine Instanz des Aspose-AI-Web-Clients, die eine Verbindung zum Standard-Aspose-LLM-Endpunkt herstellt.<br/>            Dies ist der Client, der vom parameterlosen **SlidesAIAgent.#ctor**-Konstruktor verwendet wird, sodass das explizite Erstellen<br/>            nur erforderlich ist, wenn der Client direkt an den **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            Konstruktor übergeben wird. |
| [`__init__(self, url)`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Erstellt eine Instanz des Aspose-AI-Web-Clients, die eine Verbindung zu einer benutzerdefinierten Endpunkt-URL herstellt. Verwenden Sie diese<br/>            Überladung, wenn Sie eine von dem Aspose.Slides-Team bereitgestellte URL haben; andernfalls verwenden Sie die<br/>            **AsposeAIWebClient.#ctor**-Überladung mit der Standard-URL. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Erstellt eine Konversationsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Konversationen den gesamten Kontext bei. |


### Siehe auch
* Klasse [`IAIWebClient`](/slides/python-net/de/aspose.slides.ai/iaiwebclient)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)