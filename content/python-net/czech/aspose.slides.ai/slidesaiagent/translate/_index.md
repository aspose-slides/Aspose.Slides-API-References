---
title: translate method
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Překládá prezentaci do určeného jazyka pomocí AI (synchronní verze).

```python
def translate(self, presentation, language):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation) | Cílová prezentace |
| language | **str** | Cílový jazyk |

### Poznámky

Příklad níže používá výchozí [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient), který je vytvořen
             parametrem beze vstupních parametrů **SlidesAIAgent.#ctor** konstruktorem a připojuje se k vlastnímu LLM společnosti Aspose.
             Pro použití jiného poskytovatele AI, poskytněte vlastní LLM nebo přizpůsobte připojení
             (například poskytnutím vlastního `HttpClient`), předávejte [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient)
             implementaci do **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** konstruktoru. Dostupné
             implementace zahrnují:

* [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Instance prezentace není poskytnuta |
| **RuntimeError(Proxy error(ArgumentException))** | Hodnota jazyka nesmí být None nebo prázdná |

### Viz také
* třída [`AsposeAIWebClient`](/slides/python-net/cs/aspose.slides.ai/asposeaiwebclient)
* třída [`IAIWebClient`](/slides/python-net/cs/aspose.slides.ai/iaiwebclient)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* třída [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)
* třída [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* třída [`SlidesAIAgent`](/slides/python-net/cs/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)