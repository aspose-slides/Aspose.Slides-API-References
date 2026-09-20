---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Vytvoří instanci webového klienta Aspose AI, který se připojuje k výchozímu koncovému bodu Aspose LLM.  
Toto je klient používaný v bezzákladním konstruktoru **SlidesAIAgent.#ctor**, takže jeho explicitní vytvoření je potřeba jen v případě, že se klient předává přímo konstruktoru **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**.

```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Vytvoří instanci webového klienta Aspose AI, který se připojuje k vlastní URL koncového bodu. Použijte tuto přetížení, když máte URL poskytnutou týmem Aspose.Slides; v opačném případě použijte přetížení **AsposeAIWebClient.#ctor** s výchozí URL.

```python
def __init__(self, url):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| url | **str** | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL nesmí být None nebo prázdná. |



### Viz také
* třída [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)