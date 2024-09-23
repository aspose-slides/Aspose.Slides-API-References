---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidecollection/insert_from_html/
weight: 80
---


## insert_from_html {#int-str}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Position to insert. |
| html_text | **str** | Html to add. |


## insert_from_html {#int-iorawiobase}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Position to insert. |
| html_stream | **io.RawIOBase** | A Stream object which will be used as a source of a HTML file. |


## insert_from_html {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Position to insert. |
| html_text | **str** | Html to add. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is None all external objects will be ignored. |
| uri | **str** | An URI of the specified HTML. Used to resolve relative links. |


## insert_from_html {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Position to insert. |
| html_stream | **io.RawIOBase** | A Stream object which will be used as a source of a HTML file. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is None all external objects will be ignored. |
| uri | **str** | An URI of the specified HTML. Used to resolve relative links. |



### See Also
* class [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver)
* class [`SlideCollection`](/slides/python-net/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

