---
title: Hyperlink constructor
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Crée une instance d'un hyperlien.


```python
def __init__(self, url):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| url | **str** | URL de l'hyperlien. |


## __init__(self, slide) {#islide}
Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique.
Remarque : l'hyperlien créé doit être assigné à un objet de la même présentation, sinon le lien sera enregistré comme NoAction.


```python
def __init__(self, slide):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/fr/aspose.slides/islide) | Diapositive cible. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en écrasant les propriétés secondaires.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink) | Hyperlien source |
| target_frame | **str** | Cadre cible |
| tooltip | **str** | Texte de l’infobulle |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Voir aussi
* classe [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink)
* classe [`ISlide`](/slides/python-net/fr/aspose.slides/islide)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)