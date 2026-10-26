---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Varsayılan Aspose LLM uç noktasına bağlanan bir Aspose AI web istemcisi örneği oluşturur.
            Bu, parametresiz **SlidesAIAgent.#ctor** yapıcısı tarafından kullanılan istemcidir, bu nedenle istemciyi **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** yapıcısına doğrudan geçirirken yalnızca açıkça oluşturmanız gerekir.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Özel bir uç nokta URL'sine bağlanan bir Aspose AI web istemcisi örneği oluşturur. Aspose.Slides ekibi tarafından sağlanan bir URL'niz olduğunda bu aşırı yüklü yöntemi kullanın; aksi takdirde, varsayılan URL ile **AsposeAIWebClient.#ctor** aşırı yüklü yöntemini kullanın.


```python
def __init__(self, url):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| url | **str** | Aspose LLM'nin uç nokta URL'si, Aspose.Slides ekibi tarafından sağlanır. |

### Istisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL boş veya None olamaz. |



### Ayrıca Bakınız
* sınıf [`AsposeAIWebClient`](/slides/python-net/tr/aspose.slides.ai/asposeaiwebclient)
* modül [`aspose.slides.ai`](/slides/python-net/tr/aspose.slides.ai)
* kütüphane [`Aspose.Slides`](/slides/python-net)