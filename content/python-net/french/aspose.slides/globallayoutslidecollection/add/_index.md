---
title: add method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Ajoute une nouvelle diapositive de mise en page à la présentation.

### Renvoie

Diapositive ajoutée.



```python
def add(self, master, layout_type, layout_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Diapositive maître pour une nouvelle mise en page. |
| layout_type | [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype) | Type de mise en page pour une nouvelle mise en page.<br/><br/>            Types de mise en page pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Autres types de mise en page ne sont pas pris en charge pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nom pour une nouvelle mise en page. Si le nom fourni est déjà utilisé, une ArgumentException sera levée.<br/><br/>            Si le paramètre None est fourni, le nom est généré automatiquement en fonction du type de mise en page fourni <br/><br/>            (par exemple "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Remarques

1) La mise en page ajoutée pour la valeur SlideLayoutType.Custom de `layout_type` ne contient aucun espace réservé et aucune forme.  
2) L'analogue de cette méthode est la méthode **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** accessible avec la propriété [`IMasterSlide.layout_slides`](/slides/python-net/fr/aspose.slides/imasterslide/layout_slides).

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Levée si une valeur non prise en charge du paramètre `layout_type` est fournie. Types de mise en page qui ne sont pas pris en charge pour le moment : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Levée si `master` est None. |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si `master` appartient à une autre présentation. |
| **RuntimeError(Proxy error(ArgumentException))** | Levée si la valeur du nom de mise en page `layout_name` est déjà utilisée dans <br/>            la collection des mises en page de `master`. |

### Voir aussi
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* énumération [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)