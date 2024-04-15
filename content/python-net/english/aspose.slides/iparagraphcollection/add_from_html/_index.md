---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---


## add_from_html {#string}
Adds text from specified html string to the collection.


```python
def add_from_html(self, text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| text | string | HTML text. |



## add_from_html {#string-asposeslidesimportingiexternalresourceresolver-string}
Adds text from specified html string to the collection.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| text | string | HTML text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/aspose.slides.importing/iexternalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | string | URI for adding HTML document. Used for resolving relative links. |

### Remarks

Specifying resolver can potentially introduce a vulnurability. Use with caution.



### See Also
* class [`IParagraphCollection`](/slides/python-net/aspose.slides/iparagraphcollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
