---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islidecollection/add_from_html/
weight: 30
---


## add_from_html {#str}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | Html to add. |


## add_from_html {#iorawiobase}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | A Stream object which will be used as a source of a HTML file. |


## add_from_html {#str-asposeslidesimportingiexternalresourceresolver-str}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | Html to add. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is None all external objects will be ignored. |
| uri | **str** | An URI of the specified HTML. Used to resolve relative links. |


## add_from_html {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | A Stream object which will be used as a source of a HTML file. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is None all external objects will be ignored. |
| uri | **str** | An URI of the specified HTML. Used to resolve relative links. |



### See Also
* class [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver)
* class [`ISlideCollection`](/slides/python-net/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

