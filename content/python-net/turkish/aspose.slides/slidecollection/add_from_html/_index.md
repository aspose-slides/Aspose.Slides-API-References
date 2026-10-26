---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

### Döndürür

Eklenen slaytlar



```python
def add_from_html(self, html_text):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| html_text | **str** | Eklenecek HTML. |


## add_from_html(self, html_stream) {#iorawiobase}
HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

### Döndürür

Eklenen slaytlar



```python
def add_from_html(self, html_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Bir HTML dosyasının kaynağı olarak kullanılacak bir Stream nesnesi. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

### Döndürür

Eklenen slaytlar.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| html_text | **str** | Eklenecek HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri arama nesnesi. Bu parametre None ise tüm harici nesneler yok sayılacaktır. |
| uri | **str** | Belirtilen HTML'nin bir URI'si. Göreli bağlantıları çözümlemek için kullanılır. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

### Döndürür

Eklenen slaytlar.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Bir HTML dosyasının kaynağı olarak kullanılacak bir Stream nesnesi. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri arama nesnesi. Bu parametre None ise tüm harici nesneler yok sayılacaktır. |
| uri | **str** | Belirtilen HTML'nin bir URI'si. Göreli bağlantıları çözümlemek için kullanılır. |



### Ayrıca Bakınız
* sınıf [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver)
* sınıf [`SlideCollection`](/slides/python-net/tr/aspose.slides/slidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)