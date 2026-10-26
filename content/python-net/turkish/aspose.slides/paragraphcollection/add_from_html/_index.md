---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Belirtilen html dizesinden metni koleksiyona ekler.


```python
def add_from_html(self, text):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | **str** | HTML metni. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Belirtilen html dizesinden metni koleksiyona ekler.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | **str** | HTML metni. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | URI'leri çözen ve başvurulan nesneleri getiren çözücü geri arama nesnesi. |
| uri | **str** | HTML belgesi eklemek için URI. Göreli bağlantıların çözülmesinde kullanılır. |

### Açıklamalar

Çözücü belirtilmesi potansiyel bir güvenlik açığı yaratabilir. Dikkatli kullanın.



### Ayrıca Bakınız
* sınıf [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver)
* sınıf [`ParagraphCollection`](/slides/python-net/tr/aspose.slides/paragraphcollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)