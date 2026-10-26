---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Erstellt eine Instanz des Aspose AI-Webclients, die mit dem standardmäßigen Aspose LLM-Endpunkt verbunden ist.  
Dies ist der Client, der vom parameterlosen **SlidesAIAgent.#ctor**-Konstruktor verwendet wird, sodass ein explizites Erstellen nur erforderlich ist, wenn der Client direkt an den **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-Konstruktor übergeben wird.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Erstellt eine Instanz des Aspose AI-Webclients, die mit einer benutzerdefinierten Endpunkt-URL verbunden ist. Verwenden Sie diese Überladung, wenn Ihnen eine URL vom Aspose.Slides-Team bereitgestellt wird; andernfalls verwenden Sie die **AsposeAIWebClient.#ctor**-Überladung mit der standardmäßigen URL.


```python
def __init__(self, url):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| url | **str** | Endpoint-URL des Aspose LLM, bereitgestellt vom Aspose.Slides-Team. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL darf nicht None oder leer sein. |



### Siehe auch
* Klasse [`AsposeAIWebClient`](/slides/python-net/de/aspose.slides.ai/asposeaiwebclient)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)