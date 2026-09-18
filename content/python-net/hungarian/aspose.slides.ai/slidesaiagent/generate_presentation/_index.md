---
title: generate_presentation method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Létrehoz egy prezentációpéldányt egy szöveges leírás alapján. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| description | **str** | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/hu/aspose.slides.ai/presentationcontentamounttype) | A tartalom mennyisége a létrehozott prezentációban. |

### Megjegyzés

A lenti példa az alapértelmezett [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)-t használja, amelyet a paraméter nélküli **SlidesAIAgent.#ctor** konstruktor hoz létre, és az Aspose saját LLM-jéhez csatlakozik. Egy másik AI szolgáltató használatához adja meg saját LLM-jét, vagy testreszabja a kapcsolatot (például saját `HttpClient` megadásával), adjon át egy [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítást a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** konstruktorának. Elérhető megvalósítások közé tartozik:
             
* [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Az AI csevegési utasítás nem lehet None vagy üres. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Létrehoz egy prezentációpéldányt egy szöveges leírás alapján. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a kívánt nyelven.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| description | **str** | A téma, ötletek, idézetek vagy szövegrészletek. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/hu/aspose.slides.ai/presentationcontentamounttype) | A tartalom mennyisége a létrehozott prezentációban. |
| presentation_template | [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation) | Egy prezentáció, amely elrendezési és tervezési sablonként használható, felülbírálva az alapértelmezett sablont. |

### Megjegyzés

A lenti példa az alapértelmezett [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)-t használja, amelyet a paraméter nélküli **SlidesAIAgent.#ctor** konstruktor hoz létre, és az Aspose saját LLM-jéhez csatlakozik. Egy másik AI szolgáltató használatához adja meg saját LLM-jét, vagy testreszabja a kapcsolatot (például saját `HttpClient` megadásával), adjon át egy [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítást a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** konstruktorának. Elérhető megvalósítások közé tartozik:
            
* [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | A prezentáció sablon nincs megadva. |
| **RuntimeError(Proxy error(ArgumentException))** | Az AI csevegési utasítás nem lehet None vagy üres. |

### Lásd még
* osztály [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* osztály [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient)
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)
* osztály [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* enumeráció [`PresentationContentAmountType`](/slides/python-net/hu/aspose.slides.ai/presentationcontentamounttype)
* osztály [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)