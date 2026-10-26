---
title: add_from_html method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

### Valeur de retour

Diapositives ajoutées



```python
def add_from_html(self, html_text):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| html_text | **str** | HTML à ajouter. |


## add_from_html(self, html_stream) {#iorawiobase}
Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

### Valeur de retour

Diapositives ajoutées



```python
def add_from_html(self, html_stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

### Valeur de retour

Diapositives ajoutées.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| html_text | **str** | HTML à ajouter. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est None tous les objets externes seront ignorés. |
| uri | **str** | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

### Valeur de retour

Diapositives ajoutées.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est None tous les objets externes seront ignorés. |
| uri | **str** | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |



### Voir aussi
* classe [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver)
* classe [`ISlideCollection`](/slides/python-net/fr/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)