---
title: GetTextBoxesContainsText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie tous les cadres de texte sur la diapositive spécifiée qui contiennent le texte donné.
type: docs
weight: 66
url: /fr/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) méthode


Renvoie tous les cadres de texte sur la diapositive spécifiée qui contiennent le texte donné.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | La diapositive à rechercher. |
| text | [System::String](../../../system/string/) | Le texte à rechercher dans les cadres de texte. |
| checkPlaceholderText | **bool** | Indique s’il faut inclure les cadres de texte vides, mais dont le texte de l’espace réservé contient le texte recherché. |

### Valeur de retour

Un tableau d’objets [ITextFrame](../../../aspose.slides/itextframe/) contenant le texte spécifié.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Classe [String](../../../system/string/)
* Classe [SlideUtil](../)
* Espace de noms [Aspose::Slides::Util](../../)
* Bibliothèque [Aspose.Slides](../../../)