---
title: add_from_html method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Fügt Text aus der angegebenen HTML-Zeichenkette zur Sammlung hinzu.

```python
def add_from_html(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | **str** | HTML-Text. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Fügt Text aus der angegebenen HTML-Zeichenkette zur Sammlung hinzu.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | **str** | HTML-Text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Resolver-Callback-Objekt, das URIs auflöst und referenzierte Objekte abruft. |
| uri | **str** | URI zum Hinzufügen des HTML-Dokuments. Wird zum Auflösen relativer Links verwendet. |

### Bemerkungen

Das Angeben eines Resolvers kann potenziell eine Schwachstelle einführen. Mit Vorsicht verwenden.

### Siehe auch
* Klasse [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver)
* Klasse [`ParagraphCollection`](/slides/python-net/de/aspose.slides/paragraphcollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)