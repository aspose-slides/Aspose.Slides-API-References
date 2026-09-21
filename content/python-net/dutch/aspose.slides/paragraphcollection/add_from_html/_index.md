---
title: add_from_html method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Voegt tekst toe van de opgegeven HTML-string aan de collectie.

```python
def add_from_html(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | **str** | HTML-tekst. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Voegt tekst toe van de opgegeven HTML-string aan de collectie.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | **str** | HTML-tekst. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Resolver-callbackobject dat URI’s oplost en gerefereerde objecten ophaalt. |
| uri | **str** | URI voor het toevoegen van een HTML-document. Wordt gebruikt voor het resolven van relatieve koppelingen. |

### Opmerkingen

Het specificeren van resolver kan potentieel een kwetsbaarheid introduceren. Gebruik met voorzichtigheid.

### Zie ook
* klasse [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver)
* klasse [`ParagraphCollection`](/slides/python-net/nl/aspose.slides/paragraphcollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)