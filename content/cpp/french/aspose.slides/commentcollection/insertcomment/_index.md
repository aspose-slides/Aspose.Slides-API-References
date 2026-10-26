---
title: InsertComment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère un nouveau commentaire dans une collection à l'index spécifié.
type: docs
weight: 79
url: /fr/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) méthode

Insère un nouveau commentaire dans une collection à l'index spécifié.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de l'élément dans une collection où le commentaire doit être inséré. |
| text | [System::String](../../../system/string/) | Texte brut d'un nouveau commentaire. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dans une présentation où ajouter un nouveau commentaire. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position sur une diapositive où ajouter un nouveau commentaire. |
| creationTime | [System::DateTime](../../../system/datetime/) | Heure de création d'un commentaire. |

### Valeur de retour

Commentaire inséré.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [CommentCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)