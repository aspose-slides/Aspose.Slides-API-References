---
title: add_from_html method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.

```python
def add_from_html(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | **str** | HTML-Text. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | **str** | HTML-Text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Resolver-Callback-Objekt, das URIs auflöst und referenzierte Objekte abruft. |
| uri | **str** | URI zum Hinzufügen des HTML-Dokuments. Wird zum Auflösen relativer Links verwendet. |

### Hinweise

Die Angabe eines Resolvers kann potenziell eine Schwachstelle einführen. Verwenden Sie ihn mit Vorsicht.

### Siehe auch
* Klasse [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver)
* Klasse [`IParagraphCollection`](/slides/python-net/de/aspose.slides/iparagraphcollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)