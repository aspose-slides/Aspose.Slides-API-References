---
title: translate method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Översätter en presentation till det angivna språket med AI (synkron version).


```python
def translate(self, presentation, language):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation) | Målpresentation |
| language | **str** | Målspråk |

### Anmärkningar

Exemplet nedan använder standard-[`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient), som skapas av den parameterlösa **SlidesAIAgent.#ctor**-konstruktorn och ansluter till Asposes egen LLM. För att använda en annan AI-leverantör, ange ditt eget LLM eller anpassa anslutningen (till exempel genom att tillhandahålla din egen `HttpClient`), skicka en [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)-implementation till **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-konstruktorn. Tillgängliga implementationer inkluderar:
             
* [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation-instans har inte tillhandahållits |
| **RuntimeError(Proxy error(ArgumentException))** | Språkvärdet kan inte vara None eller tomt |



### Se även
* klass [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* klass [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* klass [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)
* klass [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* klass [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* bibliotek [`Aspose.Slides`](/slides/python-net)