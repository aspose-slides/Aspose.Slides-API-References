---
title: get_font_embedding_level method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Belirtilen bayt dizisinden ve yazı tipi adından bir yazı tipinin gömme seviyesini belirler.

### Dönüş Değeri

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
* enum [`EmbeddingLevel`](/slides/python-net/tr/aspose.slides/embeddinglevel)
* sınıf [`IFontsManager`](/slides/python-net/tr/aspose.slides/ifontsmanager)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)