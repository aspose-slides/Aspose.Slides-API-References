---
title: add_from_html method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Lägger till text från en specificerad HTML-sträng till samlingen.

```python
def add_from_html(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | **str** | HTML-text. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Lägger till text från en specificerad HTML-sträng till samlingen.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | **str** | HTML-text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Resolver-callback-objekt som löser URI:er och hämtar refererade objekt. |
| uri | **str** | URI för att lägga till HTML-dokument. Används för att lösa relativa länkar. |

### Anmärkningar

Att ange en resolver kan potentiellt introducera en sårbarhet. Använd med försiktighet.

### Se även
* klass [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver)
* klass [`IParagraphCollection`](/slides/python-net/sv/aspose.slides/iparagraphcollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)