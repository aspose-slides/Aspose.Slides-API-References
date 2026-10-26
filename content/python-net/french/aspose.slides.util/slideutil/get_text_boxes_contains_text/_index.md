---
title: get_text_boxes_contains_text method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Renvoie tous les cadres de texte de la diapositive spécifiée qui contiennent le texte donné.

### Valeur de retour
Un tableau d'objets [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe) qui contiennent le texte spécifié.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | La diapositive à rechercher. |
| text | **str** | Le texte à rechercher dans les cadres de texte. |
| check_placeholder_text | **bool** | Indique s'il faut inclure les cadres de texte vides, mais dont le texte de substitution contient le texte recherché. |

### Voir aussi
* classe [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide)
* classe [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe)
* classe [`SlideUtil`](/slides/python-net/fr/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/fr/aspose.slides.util)
* bibliothèque [`Aspose.Slides`](/slides/python-net)