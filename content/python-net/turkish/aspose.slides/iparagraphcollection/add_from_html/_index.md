---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Belirtilen HTML dizesinden metni koleksiyona ekler.


```python
def add_from_html(self, text):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| text | **str** | HTML metni. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Belirtilen HTML dizesinden metni koleksiyona ekler.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| text | **str** | HTML metni. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | URI'leri çözen ve referans verilen nesneleri getiren çözümleyici geri arama nesnesi. |
| uri | **str** | HTML belgesini eklemek için URI. Göreceli bağlantıların çözülmesinde kullanılır. |

### Açıklamalar

Çözümleyici belirtilmesi potansiyel olarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın.



### Ayrıca Bakınız
* sınıf [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver)
* sınıf [`IParagraphCollection`](/slides/python-net/tr/aspose.slides/iparagraphcollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)