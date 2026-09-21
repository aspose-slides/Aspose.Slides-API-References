---
title: add_from_html method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Voegt tekst toe van opgegeven html-string aan de collectie.


```python
def add_from_html(self, text):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | **str** | HTML-tekst. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Voegt tekst toe van opgegeven html-string aan de collectie.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | **str** | HTML-tekst. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Resolver-callback-object dat URI’s oplost en verwijzende objecten ophaalt. |
| uri | **str** | URI voor het toevoegen van een HTML-document. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Opmerkingen

Het specificeren van een resolver kan mogelijk een kwetsbaarheid introduceren. Gebruik met voorzichtigheid.



### Zie ook
* klasse [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver)
* klasse [`IParagraphCollection`](/slides/python-net/nl/aspose.slides/iparagraphcollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)