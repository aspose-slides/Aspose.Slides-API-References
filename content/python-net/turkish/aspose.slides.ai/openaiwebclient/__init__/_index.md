---
title: OpenAIWebClient constructor
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
OpenAI web istemcisinin bir örneğini oluşturur.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| model | **str** | OpenAI dil modeli. Olası değerler:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API anahtarı. |
| organization_id | **str** | Organizasyon Kimliği (isteğe bağlı). |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API key değeri None ya da boş olamaz. |
| **RuntimeError(Proxy error(ArgumentException))** | Metin modeli değeri None ya da boş olamaz. |



### Ayrıca Bakınız
* sınıf [`OpenAIWebClient`](/slides/python-net/tr/aspose.slides.ai/openaiwebclient)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)