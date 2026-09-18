---
title: insert_from_html method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | HTML dosyasının kaynağı olarak kullanılacak bir Stream nesnesi. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |
| use_slide_with_index_as_start | **bool** | Bu işaretçi, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | HTML dosyasının kaynağı olarak kullanılacak bir Stream nesnesi. |
| use_slide_with_index_as_start | **bool** | Bu işaretçi, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri arama nesnesi. Bu parametre None ise tüm harici nesneler göz ardı edilir. |
| uri | **str** | Belirtilen HTML'nin URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | HTML dosyasının kaynağı olarak kullanılacak bir Stream nesnesi. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri arama nesnesi. Bu parametre None ise tüm harici nesneler göz ardı edilir. |
| uri | **str** | Belirtilen HTML'nin URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri arama nesnesi. Bu parametre None ise tüm harici nesneler göz ardı edilir. |
| uri | **str** | Belirtilen HTML'nin URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |
| use_slide_with_index_as_start | **bool** | Bu işaretçi, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konuma koleksiyona ekler.

### Dönüş
Eklenen slaytlar.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | HTML dosyasının kaynağı olarak kullanılacak bir Stream nesnesi. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri arama nesnesi. Bu parametre None ise tüm harici nesneler göz ardı edilir. |
| uri | **str** | Belirtilen HTML'nin URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |
| use_slide_with_index_as_start | **bool** | Bu işaretçi, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |



### Ayrıca Bakınız
* sınıf [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver)
* sınıf [`SlideCollection`](/slides/python-net/tr/aspose.slides/slidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)