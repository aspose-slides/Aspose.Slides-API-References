---
title: insert_from_html method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées



```python
def insert_from_html(self, index, html_text):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_text | **str** | HTML à ajouter. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_stream | **io.RawIOBase** | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_text | **str** | HTML à ajouter. |
| use_slide_with_index_as_start | **bool** | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index indiqué.<br/><br/>            Si **true**, l’insertion des données commencera dans un espace vide sur la diapositive avec l'index indiqué.<br/><br/>            Si **false**, les données seront ajoutées aux diapositives créées. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_stream | **io.RawIOBase** | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| use_slide_with_index_as_start | **bool** | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index indiqué.<br/><br/>            Si **true**, l’insertion des données commencera dans un espace vide sur la diapositive avec l'index indiqué.<br/><br/>            Si **false**, les données seront ajoutées aux diapositives créées. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_text | **str** | HTML à ajouter. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour extraire des objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| uri | **str** | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_stream | **io.RawIOBase** | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour extraire des objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| uri | **str** | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_text | **str** | HTML à ajouter. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour extraire des objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| uri | **str** | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| use_slide_with_index_as_start | **bool** | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index indiqué.<br/><br/>            Si **true**, l’insertion des données commencera dans un espace vide sur la diapositive avec l'index indiqué.<br/><br/>            Si **false**, les données seront ajoutées aux diapositives créées. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

### Renvoie

Diapositives ajoutées.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Position d'insertion. |
| html_stream | **io.RawIOBase** | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Un objet de rappel utilisé pour extraire des objets externes. Si ce paramètre est None, tous les objets externes seront ignorés. |
| uri | **str** | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| use_slide_with_index_as_start | **bool** | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index indiqué.<br/><br/>            Si **true**, l’insertion des données commencera dans un espace vide sur la diapositive avec l'index indiqué.<br/><br/>            Si **false**, les données seront ajoutées aux diapositives créées. |



### Voir aussi
* classe [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver)
* classe [`ISlideCollection`](/slides/python-net/fr/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)