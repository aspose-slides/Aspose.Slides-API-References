---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozásán keresztül
description: 
type: docs
url: /hu/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Létrehozza az Aspose AI webkliens egy példányát, amely a alapértelmezett Aspose LLM végponthoz kapcsolódik. Ez a klienst a paraméter nélküli **SlidesAIAgent.#ctor** konstruktor használja, így az explicit létrehozása csak akkor szükséges, ha a klienst közvetlenül át szeretnénk adni a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** konstruktorának.

```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Létrehozza az Aspose AI webkliens egy példányát, amely egy egyedi végpont URL-hez kapcsolódik. Használja ezt a túlterhelést, ha az Aspose.Slides csapat által biztosított URL-vel rendelkezik; egyébként használja a **AsposeAIWebClient.#ctor** túlterhelést az alapértelmezett URL-lel.

```python
def __init__(self, url):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| url | **str** | Az Aspose LLM végpont URL-je, amelyet az Aspose.Slides csapat biztosít. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Az URL nem lehet None vagy üres. |



### Lásd még
* osztály [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)