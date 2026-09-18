---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
OpenAI uyumlu web istemcisinin bir örneğini oluşturur.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| model | **str** | LLM sağlayıcısı tarafından desteklenen model adı. |
| api_key | **str** | API anahtarı (token). |
| base_url | **str** | OpenAI uyumlu LLM'nin temel URL'si. |

### İstisnalar

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API anahtarı değeri None veya boş olamaz. |
| **RuntimeError(Proxy error(ArgumentException))** | Metin modeli değeri None veya boş olamaz. |
| **RuntimeError(Proxy error(ArgumentException))** | Temel URL değeri None veya boş olamaz. |



### Ayrıca Bakınız
* sınıf [`OpenAICompatibleWebClient`](/slides/python-net/tr/aspose.slides.ai/openaicompatiblewebclient)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)