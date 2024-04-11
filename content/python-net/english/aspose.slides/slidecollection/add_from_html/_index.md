---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidecollection/add_from_html/
weight: 70
---


## add_from_html {#string}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides.



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | string | Html to add. |



## add_from_html {#System.IO.Stream}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides.



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | System.IO.Stream |  |



## add_from_html {#string-aspose.slides.importing.IExternalResourceResolver-string}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | string | Html to add. |
| resolver | [`IExternalResourceResolver`]/slides/python-net/aspose.slides.importing/iexternalresourceresolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | string | An URI of the specified HTML. Used to resolve relative links. |



## add_from_html {#System.IO.Stream-aspose.slides.importing.IExternalResourceResolver-string}
Creates slides from HTML text and adds them to the end of the collection.

### Returns

Added slides.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | System.IO.Stream |  |
| resolver | [`IExternalResourceResolver`]/slides/python-net/aspose.slides.importing/iexternalresourceresolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | string | An URI of the specified HTML. Used to resolve relative links. |



