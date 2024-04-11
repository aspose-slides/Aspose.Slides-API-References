---
title: insert_from_html method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/slidecollection/insert_from_html/
weight: 80
---


## insert_from_html {#int-string}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides.



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Position to insert. |
| html_text | string | Html to add. |



## insert_from_html {#int-System.IO.Stream}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides.



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Position to insert. |
| html_stream | System.IO.Stream |  |



## insert_from_html {#int-string-aspose.slides.importing.IExternalResourceResolver-string}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Position to insert. |
| html_text | string | Html to add. |
| resolver | [`IExternalResourceResolver`]/slides/python-net/aspose.slides.importing/iexternalresourceresolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | string | An URI of the specified HTML. Used to resolve relative links. |



## insert_from_html {#int-System.IO.Stream-aspose.slides.importing.IExternalResourceResolver-string}
Creates slides from HTML text and inserts them to the collection at the specified position.

### Returns

Added slides.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Position to insert. |
| html_stream | System.IO.Stream |  |
| resolver | [`IExternalResourceResolver`]/slides/python-net/aspose.slides.importing/iexternalresourceresolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | string | An URI of the specified HTML. Used to resolve relative links. |



