---
title: translate method
second_title: Aspose.Slides Python számára a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Átfordít egy prezentációt a megadott nyelvre AI segítségével (szinkron verzió).

```python
def translate(self, presentation, language):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) | Célprezentáció |
| language | **str** | Célnyelv |

### Megjegyzések

Az alábbi példa az alapértelmezett [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)-t használja, amelyet a
             paraméter nélküli **SlidesAIAgent.#ctor** konstruktor hoz létre, és
             az Aspose saját LLM-jéhez csatlakozik.
             Egy másik AI szolgáltató használatához adja meg saját LLM-jét, vagy
             testreszabja a kapcsolatot (például a saját `HttpClient` megadásával), és egy [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient)
             megvalósítást ad át a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** konstruktorának. Elérhető
             megvalósítások:

* [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | A prezentáció példány nincs megadva |
| **RuntimeError(Proxy error(ArgumentException))** | A nyelvérték nem lehet None vagy üres |

### Lásd még
* osztály [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* osztály [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)
* osztály [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* osztály [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)