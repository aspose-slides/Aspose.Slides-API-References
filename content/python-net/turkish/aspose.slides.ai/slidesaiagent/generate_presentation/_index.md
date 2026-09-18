---
title: generate_presentation method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Metin açıklamasından bir sunum örneği oluşturur. Gerekli dilde bir konu, fikir, alıntı veya metin parçacığı sağlayın.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| description | **str** | Konu, fikir, alıntı veya metin parçacıkları. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/tr/aspose.slides.ai/presentationcontentamounttype) | Oluşturulan sunumdaki içerik miktarı. |

### Açıklamalar

Aşağıdaki örnek, varsayılan [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)'ı kullanır; bu, parametresiz **SlidesAIAgent.#ctor** yapıcısı tarafından oluşturulur ve Aspose'un kendi LLM'sine bağlanır. Farklı bir AI sağlayıcı kullanmak için kendi LLM'nizi sağlayın veya bağlantıyı özelleştirin (örneğin, kendi `HttpClient`'ınızı sağlayarak), **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** yapıcısına bir [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient) uygulaması geçirin. Mevcut uygulamalar şunlardır:
             
* [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI sohbet talimatı None veya boş olamaz. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Metin açıklamasından bir sunum örneği oluşturur. Gerekli dilde bir konu, fikir, alıntı veya metin parçacığı sağlayın.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| description | **str** | Konu, fikir, alıntı veya metin parçacıkları. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/tr/aspose.slides.ai/presentationcontentamounttype) | Oluşturulan sunumdaki içerik miktarı. |
| presentation_template | [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) | Yerleşim ve tasarım için şablon olarak kullanılacak bir sunum, varsayılan şablonun yerine geçer. |

### Açıklamalar

Aşağıdaki örnek, varsayılan [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)'ı kullanır; bu, parametresiz **SlidesAIAgent.#ctor** yapıcısı tarafından oluşturulur ve Aspose'un kendi LLM'sine bağlanır. Farklı bir AI sağlayıcı kullanmak için kendi LLM'nizi sağlayın veya bağlantıyı özelleştirin (örneğin, kendi `HttpClient`'ınızı sağlayarak), **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** yapıcısına bir [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient) uygulaması geçirin. Mevcut uygulamalar şunlardır:
            
* [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Sunum şablonu sağlanmadı. |
| **RuntimeError(Proxy error(ArgumentException))** | AI sohbet talimatı None veya boş olamaz. |



### Bakınız
* sınıf [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* sınıf [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)
* sınıf [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* enum [`PresentationContentAmountType`](/slides/python-net/tr/aspose.slides.ai/presentationcontentamounttype)
* sınıf [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)