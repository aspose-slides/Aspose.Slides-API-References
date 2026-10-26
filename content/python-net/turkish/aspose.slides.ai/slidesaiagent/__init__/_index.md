---
title: SlidesAIAgent constructor
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Yeni bir [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent) örneğini, yerleşik [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient) ve varsayılan yapılandırması ile başlatır. İstemci, Aspose'un kendi LLM'sine bağlanır ve ek yapılandırma gerektirmez. Farklı bir AI istemcisi kullanmak için **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** aşırı yüklemesini kullanın.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Yeni bir [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent) örneğini özel bir AI istemcisi ile başlatır. Bu aşırı yüklemeyi AI sağlayıcısını belirlemek, kendi LLM'nizi sağlamak veya bağlantıyı özelleştirmek (örneğin, kendi `HttpClient`'ınızı sağlayarak) için kullanın. [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)'in herhangi bir uygulaması kullanılabilir, örnek olarak:

* [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)

Yerleşik [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)'yu varsayılan yapılandırmasıyla kullanmak için **SlidesAIAgent.#ctor** aşırı yüklemesini kullanın.

```python
def __init__(self, ai_client):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient) | AI istemci örneği. [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)'in herhangi bir uygulaması kullanılabilir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI istemci örneği sağlanmamıştır. |

### See Also
* sınıf [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* sınıf [`IAIWebClient`](/slides/python-net/tr/aspose.slides.ai/iaiwebclient)
* sınıf [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)
* sınıf [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* sınıf [`SlidesAIAgent`](/slides/python-net/tr/aspose.slides.ai/slidesaiagent)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)