---
title: add_from_html method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
A megadott HTML-karakterláncból szöveget ad a gyűjteményhez.

```python
def add_from_html(self, text):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| text | **str** | HTML szöveg. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
A megadott HTML-karakterláncból szöveget ad a gyűjteményhez.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| text | **str** | HTML szöveg. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Az URI-k feloldásáért és a hivatkozott objektumok lekéréséért felelős resolver visszahívási objektum. |
| uri | **str** | URI a HTML-dokumentum hozzáadásához. Relatív hivatkozások feloldásához használatos. |

### Megjegyzés

A resolver megadása potenciálisan sebezhetőséget eredményezhet. Óvatosan használja.

### Lásd még
* osztály [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver)
* osztály [`ParagraphCollection`](/slides/python-net/hu/aspose.slides/paragraphcollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)