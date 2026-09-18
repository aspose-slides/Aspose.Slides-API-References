---
title: get_font_embedding_level method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Verilen bayt dizisi ve yazı tipi adı kullanılarak bir yazı tipinin gömme seviyesini belirler.

### Döndürür
Belirtilen yazı tipinin gömme seviyesi.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_bytes | **bytes** | Yazı tipi verilerini içeren bayt dizisi. |
| font_name | **str** | Yazı tipinin adı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `font_bytes` None olduğunda atılır. |



### Ayrıca Bakınız
* enumerasyon [`EmbeddingLevel`](/slides/python-net/tr/aspose.slides/embeddinglevel)
* sınıf [`FontsManager`](/slides/python-net/tr/aspose.slides/fontsmanager)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)