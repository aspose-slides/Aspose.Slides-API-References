---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islidecollection/add_from_html/
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
| html_stream | **io.RawIOBase** | HTML dosyasının kaynağı olarak kullanılacak bir Akış nesnesi. |


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
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Dış nesneleri getirmek için kullanılan bir geri çağırma nesnesi. Bu parametre None ise tüm dış nesneler yok sayılır. |
| uri | **str** | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |


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
| html_stream | **io.RawIOBase** | HTML dosyasının kaynağı olarak kullanılacak bir Akış nesnesi. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Dış nesneleri getirmek için kullanılan bir geri çağırma nesnesi. Bu parametre None ise tüm dış nesneler yok sayılır. |
| uri | **str** | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |



### Ayrıca Bakınız
* sınıf [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver)
* sınıf [`ISlideCollection`](/slides/python-net/tr/aspose.slides/islidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)