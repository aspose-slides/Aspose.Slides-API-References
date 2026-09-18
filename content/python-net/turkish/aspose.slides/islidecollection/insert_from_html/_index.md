---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides

```python
def insert_from_html(self, index, html_text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |

## insert_from_html(self, index, html_stream) {#int-iorawiobase}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides

```python
def insert_from_html(self, index, html_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | Bir Stream nesnesi, HTML dosyasının kaynağı olarak kullanılacak. |

## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides

```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |
| use_slide_with_index_as_start | **bool** | Bu bayrak, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |

## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides

```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | Bir Stream nesnesi, HTML dosyasının kaynağı olarak kullanılacak. |
| use_slide_with_index_as_start | **bool** | Bu bayrak, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |

## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides.

```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri çağırma nesnesi. Bu parametre **None** ise tüm harici nesneler yoksayılacak. |
| uri | **str** | Belirtilen HTML'in bir URI'si. Göreli bağlantıları çözümlemek için kullanılır. |

## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides.

```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | Bir Stream nesnesi, HTML dosyasının kaynağı olarak kullanılacak. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri çağırma nesnesi. Bu parametre **None** ise tüm harici nesneler yoksayılacak. |
| uri | **str** | Belirtilen HTML'in bir URI'si. Göreli bağlantıları çözümlemek için kullanılır. |

## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides.

```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_text | **str** | Eklenecek HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri çağırma nesnesi. Bu parametre **None** ise tüm harici nesneler yoksayılacak. |
| uri | **str** | Belirtilen HTML'in bir URI'si. Göreli bağlantıları çözümlemek için kullanılır. |
| use_slide_with_index_as_start | **bool** | Bu bayrak, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |

## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
HTML metninden slaytlar oluşturur ve bunları belirtilen konumda koleksiyona ekler.

### Returns
Added slides.

```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Eklenecek konum. |
| html_stream | **io.RawIOBase** | Bir Stream nesnesi, HTML dosyasının kaynağı olarak kullanılacak. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan bir geri çağırma nesnesi. Bu parametre **None** ise tüm harici nesneler yoksayılacak. |
| uri | **str** | Belirtilen HTML'in bir URI'si. Göreli bağlantıları çözümlemek için kullanılır. |
| use_slide_with_index_as_start | **bool** | Bu bayrak, eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı.<br/><br/>            Eğer **true** ise, veri ekleme belirtilen indeksli slaytta boş bir alandan başlayacaktır.<br/><br/>            Eğer **false** ise, veri oluşturulan slaytlara eklenecektir. |

### See Also
* sınıf [`IExternalResourceResolver`](/slides/python-net/tr/aspose.slides.importing/iexternalresourceresolver)
* sınıf [`ISlideCollection`](/slides/python-net/tr/aspose.slides/islidecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)