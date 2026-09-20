---
title: generate_presentation method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Genererar en presentationsinstans från en textbeskrivning. Ange ett ämne, idéer, citat eller textutdrag på det önskade språket.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| description | **str** | Ämnet, idéerna, citaten eller textutdragen. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/sv/aspose.slides.ai/presentationcontentamounttype) | Mängden innehåll i den resulterande presentationen. |

### Anmärkningar

Exemplet nedan använder standard [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient), som skapas av den  
parametrolösa **SlidesAIAgent.#ctor**-konstruktorn och ansluter till Asposes egen LLM.  
För att använda en annan AI-leverantör, ange din egen LLM eller anpassa anslutningen  
(till exempel genom att tillhandahålla din egen `HttpClient`), skicka en [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)  
implementation till **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-konstruktorn. Tillgängliga  
implementationer inkluderar:
             
* [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI-chattinstruktionen kan inte vara None eller tom. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Genererar en presentationsinstans från en textbeskrivning. Ange ett ämne, idéer, citat eller textutdrag på det önskade språket.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| description | **str** | Ämnet, idéerna, citaten eller textutdragen. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/sv/aspose.slides.ai/presentationcontentamounttype) | Mängden innehåll i den resulterande presentationen. |
| presentation_template | [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation) | En presentation som ska användas som mall för layout och design, och ersätter standardmallen. |

### Anmärkningar

Exemplet nedan använder standard [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient), som skapas av den  
parametrolösa **SlidesAIAgent.#ctor**-konstruktorn och ansluter till Asposes egen LLM.  
För att använda en annan AI-leverantör, ange din egen LLM eller anpassa anslutningen  
(till exempel genom att tillhandahålla din egen `HttpClient`), skicka en [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)  
implementation till **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**-konstruktorn. Tillgängliga  
implementationer inkluderar:
            
* [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentationsmall är inte angiven. |
| **RuntimeError(Proxy error(ArgumentException))** | AI-chattinstruktionen kan inte vara None eller tom. |



### Se även
* klass [`AsposeAIWebClient`](/slides/python-net/sv/aspose.slides.ai/asposeaiwebclient)
* klass [`IAIWebClient`](/slides/python-net/sv/aspose.slides.ai/iaiwebclient)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* klass [`OpenAICompatibleWebClient`](/slides/python-net/sv/aspose.slides.ai/openaicompatiblewebclient)
* klass [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* enumeration [`PresentationContentAmountType`](/slides/python-net/sv/aspose.slides.ai/presentationcontentamounttype)
* klass [`SlidesAIAgent`](/slides/python-net/sv/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* bibliotek [`Aspose.Slides`](/slides/python-net)