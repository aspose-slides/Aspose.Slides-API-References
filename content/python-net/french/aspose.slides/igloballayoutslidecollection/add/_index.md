---
title: add method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Ajoute une nouvelle diapositive de disposition à la présentation.

### Retour

Diapositive ajoutée.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide) | Diapositive maître pour une nouvelle disposition. |
| layout_type | [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype) | Type de disposition pour une nouvelle disposition.<br/><br/> Types de disposition pris en charge : Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> Autres types de disposition non pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nom pour une nouvelle disposition. Si le nom fourni est déjà utilisé, une ArgumentException sera levée.<br/><br/> Si le paramètre None est passé, alors le nom est généré automatiquement en fonction du type de disposition fourni <br/><br/> (par exemple "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Remarques

1) La disposition ajoutée pour la valeur SlideLayoutType.Custom de `layout_type` ne contient aucun espace réservé et aucune forme.
            2) L'analogue de cette méthode est la méthode **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** accédée via la propriété [`IMasterSlide.layout_slides`](/slides/python-net/fr/aspose.slides/imasterslide/layout_slides).

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Lancée si une valeur non prise en charge du paramètre `layout_type` est fournie. Types de disposition non pris en charge actuellement : Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lancée si `master` est None. |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée si `master` appartient à une autre présentation. |
| **RuntimeError(Proxy error(ArgumentException))** | Lancée si la valeur du nom de disposition `layout_name` est déjà utilisée dans <br/>            la collection des dispositions de `master`. |



### Voir aussi
* classe [`IGlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/igloballayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/fr/aspose.slides/imasterslide)
* énumération [`SlideLayoutType`](/slides/python-net/fr/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)