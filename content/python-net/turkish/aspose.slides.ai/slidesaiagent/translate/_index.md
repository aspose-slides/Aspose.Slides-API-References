---
title: translate method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
AI kullanarak belirtilen dile bir sunumu çevirir (senkron sürüm).


```python
def translate(self, presentation, language):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) | Hedef sunum |
| language | **str** | Hedef dil |

### Açıklamalar

Aşağıdaki örnek, parametresiz **SlidesAIAgent.#ctor** yapıcısı tarafından oluşturulan ve Aspose'un kendi LLM'sine bağlanan varsayılan [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)'yi kullanır. Farklı bir AI sağlayıcı kullanmak için kendi LLM'nizi sağlayın veya bağlantıyı özelleştirin (örneğin, kendi `HttpClient`'ınızı sağlayarak), **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** yapıcısına bir [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient) uygulaması geçirin. Mevcut uygulamalar şunlardır:
             
* [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation instance is not provided |
| **RuntimeError(Proxy error(ArgumentException))** | Language value can't be None or empty |



### Ayrıca Bakınız
* sınıf [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* sınıf [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)
* sınıf [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* sınıf [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)