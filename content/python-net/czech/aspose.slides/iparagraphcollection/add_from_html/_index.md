---
title: add_from_html method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Přidá text ze zadaného řetězce HTML do kolekce.

```python
def add_from_html(self, text):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| text | **str** | HTML text. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Přidá text ze zadaného řetězce HTML do kolekce.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| text | **str** | HTML text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt callback resolveru, který řeší URI a načítá odkazované objekty. |
| uri | **str** | URI pro přidání HTML dokumentu. Používá se k řešení relativních odkazů. |

### Poznámky

Zadání resolveru může potenciálně představovat zranitelnost. Používejte s opatrností.

### Viz také
* třída [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver)
* třída [`IParagraphCollection`](/slides/python-net/cs/aspose.slides/iparagraphcollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)