---
title: generate_presentation method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Vytvoří instanci prezentace z textového popisu. Poskytněte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| description | **str** | Téma, nápady, citáty nebo úryvky textu. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/cs/aspose.slides.ai/presentationcontentamounttype) | Množství obsahu ve výsledné prezentaci. |

### Poznámky

Níže uvedený příklad používá výchozí [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient), který je vytvořen bezparametrovým konstruktor **SlidesAIAgent.#ctor** a připojuje se k vlastnímu LLM společnosti Aspose. Pro použití jiného poskytovatele AI, dodat vlastní LLM nebo přizpůsobit připojení (například poskytnutím vlastního `HttpClient`), předáte implementaci [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient) do konstruktoru **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. K dispozici jsou následující implementace:
             
* [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Instrukce AI chatu nesmí být None nebo prázdná. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Vytvoří instanci prezentace z textového popisu. Poskytněte téma, nápady, citáty nebo úryvky textu v požadovaném jazyce.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| description | **str** | Téma, nápady, citáty nebo úryvky textu. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/cs/aspose.slides.ai/presentationcontentamounttype) | Množství obsahu ve výsledné prezentaci. |
| presentation_template | [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) | Prezentace, která se použije jako šablona pro rozvržení a design, nahrazující výchozí šablonu. |

### Poznámky

Níže uvedený příklad používá výchozí [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient), který je vytvořen bezparametrovým konstruktor **SlidesAIAgent.#ctor** a připojuje se k vlastnímu LLM společnosti Aspose. Pro použití jiného poskytovatele AI, dodat vlastní LLM nebo přizpůsobit připojení (například poskytnutím vlastního `HttpClient`), předáte implementaci [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient) do konstruktoru **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. K dispozici jsou následující implementace:
            
* [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Šablona prezentace není poskytnuta. |
| **RuntimeError(Proxy error(ArgumentException))** | Instrukce AI chatu nesmí být None nebo prázdná. |



### Viz také
* třída [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* třída [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* třída [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)
* třída [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* enumerace [`PresentationContentAmountType`](/slides/python-net/cs/aspose.slides.ai/presentationcontentamounttype)
* třída [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)