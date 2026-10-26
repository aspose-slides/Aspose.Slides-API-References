---
title: add method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Ajoute une nouvelle diapositive de mise en page à la fin de la collection.

### Renvoie

Diapositive ajoutée.

```python
def add(self, layout_type, layout_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype) | Type de mise en page pour une nouvelle mise en page.<br/><br/>            Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Autres types de mise en page non pris en charge pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée.<br/><br/>            Si le paramètre None est fourni, le nom est généré automatiquement en fonction du type de mise en page fourni <br/><br/>            (par exemple "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Remarques

1) La mise en page ajoutée pour la valeur SlideLayoutType.Custom de `layout_type` ne contient aucun espace réservé ni aucune forme.  
2) L'analogue de cette méthode est la méthode **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** accessible via la propriété [`IPresentation.layout_slides`](/slides/python-net/fr/aspose.slides/ipresentation/layout_slides).

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Lancée si une valeur non prise en charge du paramètre `layout_type` est fournie. Types de mise en page non pris en charge pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée si la valeur du nom de mise en page `layout_name` est déjà utilisée dans <br/>            cette collection de mises en page. |

### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/imasterlayoutslidecollection)
* énumération [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)