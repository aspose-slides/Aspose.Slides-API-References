---
title: SlidesAIAgent class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozásban
description: 
type: docs
url: /hu/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent osztály

AI-alapú funkciókat biztosít a prezentációk feldolgozásához.

A SlidesAIAgent típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Inicializál egy új példányt a(z) [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent) egy egyedi AI klienssel.<br/>            Használja ezt a túltöltést az AI szolgáltató megadásához, saját LLM biztosításához, vagy a<br/>            kapcsolat testreszabásához (például saját `HttpClient` megadásával).<br/>            Bármely [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient) megvalósítás használható, beleértve:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            A beépített [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient) alapértelmezett konfigurációjának használatához,<br/>            használja a **SlidesAIAgent.#ctor** túltöltést helyette. |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent/__init__/#) | Inicializál egy új példányt a(z) [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent) a beépített<br/>            [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient) alapértelmezett konfigurációjával. A kliens csatlakozik<br/>            az Aspose saját LLM-jéhez, és nem igényel további konfigurációt.<br/>            Egy másik AI kliens használatához, használja a **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** túltöltést helyette. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Létrehoz egy prezentáció példányt egy szöveges leírás alapján. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a szükséges nyelven. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Létrehoz egy prezentáció példányt egy szöveges leírás alapján. Adjon meg egy témát, ötleteket, idézeteket vagy szövegrészleteket a szükséges nyelven. |
| [`translate(self, presentation, language)`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Lefordít egy prezentációt a megadott nyelvre AI segítségével (szinkron változat). |

### Lásd még
* osztály [`AsposeAIWebClient`](/slides/python-net/hu/aspose.slides.ai/asposeaiwebclient)
* osztály [`IAIWebClient`](/slides/python-net/hu/aspose.slides.ai/iaiwebclient)
* osztály [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)
* osztály [`OpenAIWebClient`](/slides/python-net/hu/aspose.slides.ai/openaiwebclient)
* osztály [`SlidesAIAgent`](/slides/python-net/hu/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)