---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Maakt een instantie van de Aspose AI-webclient die verbinding maakt met de standaard Aspose LLM-endpoint.  
Dit is de client die wordt gebruikt door de parameterloze **SlidesAIAgent.#ctor**-constructor, dus expliciet aanmaken is alleen nodig wanneer de client rechtstreeks wordt doorgegeven aan de **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-constructor direct.



```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste endpoint-URL. Gebruik deze overload wanneer je een door het Aspose.Slides-team geleverde URL hebt; gebruik anders de **AsposeAIWebClient.#ctor**-overload met de standaard-URL.


```python
def __init__(self, url):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| url | **str** | Endpoint-URL van de Aspose LLM, verstrekt door het Aspose.Slides-team. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL mag niet None of leeg zijn. |



### Zie ook
* klasse [`AsposeAIWebClient`](/slides/python-net/nl/aspose.slides.ai/asposeaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* bibliotheek [`Aspose.Slides`](/slides/python-net)