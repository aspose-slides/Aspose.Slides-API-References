---
title: insert method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Insère une nouvelle diapositive de mise en page à la position spécifiée de la collection.

### Valeur retournée

Diapositive insérée.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Index de la nouvelle diapositive. |
| layout_type | [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype) | Type de mise en page pour une nouvelle mise en page.<br/><br/>            Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Les autres types de mise en page ne sont pas pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée.<br/><br/>            Si le paramètre None est passé, alors le nom est généré automatiquement en fonction du type de mise en page fourni <br/><br/>            (par exemple "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Remarques

La mise en page insérée pour la valeur SlideLayoutType.Custom de `layout_type` ne contient aucun espace réservé et aucune forme.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Levée si une valeur non prise en charge du paramètre `layout_type` est fournie. Types de mise en page qui ne sont pas pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si la valeur du nom de mise en page `layout_name` est déjà utilisée dans <br/>            cette collection de mises en page. |



### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection)
* énumération [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)