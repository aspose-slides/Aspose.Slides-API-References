---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Skapar en instans av Aspose AI-webbklienten som ansluter till standard-Aspose LLM-slutpunkten.  
Detta är klienten som används av den parameterlösa **SlidesAIAgent.#ctor**-konstruktorn, så att skapa den explicit är endast nödvändigt när klienten skickas till **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-konstruktorn direkt.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Skapar en instans av Aspose AI-webbklienten som ansluter till en anpassad slutpunkts-URL. Använd denna överlagring när du har en URL som tillhandahålls av Aspose.Slides-teamet; annars, använd **AsposeAIWebClient.#ctor**-överlagringen med standard-URL.


```python
def __init__(self, url):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| url | **str** | Slutpunkts-URL för Aspose LLM, tillhandahållen av Aspose.Slides-teamet. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL får inte vara None eller tom. |



### Se också
* klass [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* bibliotek [`Aspose.Slides`](/slides/python-net)